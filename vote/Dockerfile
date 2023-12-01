FROM python:3.9-alpine
LABEL OWNER="TOB-GROUP-SOLUTIONS"
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt
COPY . /app
EXPOSE 80
CMD ["python", "app.py"]