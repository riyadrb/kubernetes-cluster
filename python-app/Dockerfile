
FROM python:3.8-slim

ENV DJANGO_SETTINGS_MODULE=myapp.settings

ENV PYTHONUNBUFFERED 1

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]

