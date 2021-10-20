FROM python:3.8
ENV PYTHONUNBUFFERED 1
RUN mkdir /temp
WORKDIR /temp
COPY requirements.txt /temp/
RUN pip install -r requirements.txt
COPY . /code/