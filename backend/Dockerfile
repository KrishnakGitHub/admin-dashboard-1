FROM python:3.12.0a1-bullseye
WORKDIR /backend

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .