FROM python:3.10-slim

WORKDIR /app

COPY .CI_CD/CD/  /app

WORKDIR /app
RUN ls

EXPOSE 8080

cmd ["python", "app.py"]