FROM python:3.9

LABEL maintainer="Yegane Amirjani yeganeh.a.m7979@gmail.com"

WORKDIR /producer

COPY . /producer
RUN python -m pip install --upgrade pip && pip install kafka-python

CMD [ "python3", "producer.py" ]
