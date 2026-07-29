FROM python:3.8-slim-buster 

COPY requirments.txt /app/requirments.txt

RUN pip install -r /app/requirments.txt

COPY . /app

WORKDIR /app

ENTRYPOINT [ "python" ]

CMD ["app.py"]