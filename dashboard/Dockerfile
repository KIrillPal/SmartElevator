FROM python:3.10

WORKDIR /service

COPY ./requirements.txt /service/requirements.txt

RUN pip install -r /service/requirements.txt \
    && rm -rf /root/.cache/pip

COPY . /service/
