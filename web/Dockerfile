
FROM python:3.11

RUN pip install pipenv

COPY . /app

WORKDIR /app

RUN pip install flask psycopg

CMD ["python", "app.py"]