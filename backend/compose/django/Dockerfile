FROM python:3.8-slim
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD backend/requirements/base.txt backend/requirements/dev.txt /code/
RUN pip install -r base.txt -r dev.txt
ADD /backend/ /code/
