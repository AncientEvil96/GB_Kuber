FROM python:3.9

RUN apt update -y

RUN apt install -y build-essential

ADD  . /app

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 5000

ENTRYPOINT python app.py runserver 0.0.0.0:5000