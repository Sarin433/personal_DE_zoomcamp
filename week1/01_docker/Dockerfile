FROM python:3.9.13

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app
COPY ny_ingestion.py ny_ingestion.py 

ENTRYPOINT [ "python", "ny_ingestion.py" ]