FROM python:3.9-slim

ENV PYTHONUNBUFFERED=1
USER root

RUN pip install poetry
RUN pip install --upgrade pip
RUN python -m pip install fastapi gunicorn uvicorn[standard]

RUN poetry config virtualenvs.create false

WORKDIR /app