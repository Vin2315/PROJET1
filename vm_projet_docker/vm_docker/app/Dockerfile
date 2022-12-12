FROM python:3.9

RUN mkdir -p /app

WORKDIR /app

COPY app.py /app

COPY requirements.txt /app

RUN pip install -r requirements.txt

CMD ["python", "app.py"]

