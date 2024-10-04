# Use the official Python 3.9 image
FROM python:3.9

WORKDIR /app
COPY Docker-Blog/requirements.txt /app/requirements.txt
RUN pip install -r /app/requirements.txt

COPY Volume-Blog/ /app

EXPOSE 8080

# Run the Flask application
CMD ["python", "app.py"]
