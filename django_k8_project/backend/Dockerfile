FROM python:5.0

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY myapp myapp

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
