FROM python:3.9-alpine

ADD . /app

RUN pip install -r /app/requirements.txt

EXPOSE 8080

ENTRYPOINT python /app/app.py runserver 8080
