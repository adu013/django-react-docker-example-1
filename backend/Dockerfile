FROM python:3.12.0a7-bullseye

ENV PYTHONUNBUFFERED=1

WORKDIR /backend

COPY . .

RUN pip install django django-cors-headers

EXPOSE 8080
