FROM python:3.7
WORKDIR /code
COPY requirements.txt .

RUN pip install -r requirements.txt

COPY src/ .

CMD ["python", "./server.py"]
