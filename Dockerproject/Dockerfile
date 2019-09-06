FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /mydjango
WORKDIR /mydjango
COPY requirements.txt /mydjango/
RUN pip install -r requirements.txt
COPY . /mydjango/


