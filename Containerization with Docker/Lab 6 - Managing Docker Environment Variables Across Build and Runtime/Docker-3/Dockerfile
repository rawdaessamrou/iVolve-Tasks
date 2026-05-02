FROM python:3.9-slim

WORKDIR /app

COPY . /app

RUN pip install flask

EXPOSE 8080

ENV APP_MODE=production
ENV APP_REGION=canada-west

CMD ["python", "app.py"]
