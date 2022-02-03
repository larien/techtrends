FROM python:3.8

LABEL maintainer="larien.dev"

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 3111

RUN [ "python", "init_db.py" ]

CMD [ "python", "app.py" ]