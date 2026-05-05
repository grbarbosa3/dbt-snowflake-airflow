FROM python:3.12-slim

WORKDIR /app

COPY dbt/ /app/

RUN rm -rf /app/target /app/logs

RUN pip install --upgrade pip && \
    pip install dbt && \
    pip install dbt-snowflake

CMD ["bash"]
