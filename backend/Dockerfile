FROM python

ADD  requirements.txt /app/requirements.txt

RUN pip install -r /app/requirements.txt

ADD . /app

WORKDIR /app

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]