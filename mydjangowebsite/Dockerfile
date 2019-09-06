FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /mydjangowebsite
WORKDIR /mydjangowebsite
COPY requirements.txt /mydjangowebsite/
RUN pip install -r requirements.txt
COPY . /mydjangowebsite/
