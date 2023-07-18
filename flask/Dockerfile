# Use the official Python base image
FROM python:3.9-slim
# Set the working directory inside the container
WORKDIR /app
# Copy the Python script into the container
COPY hello.py .
# Install any necessary dependencies
RUN pip install flask
# Set the command to run the Python application
CMD ["python3", "hello.py"]

EXPOSE 8080
