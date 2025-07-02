FROM python:3.12

WORKDIR /app

COPY . /app
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8050

CMD gunicorn 0.0.0.0:8050 main:server
