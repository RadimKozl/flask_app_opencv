# Use an official Python runtime as a parent image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /app

COPY docker-requirements.txt /app/docker-requirements.txt

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r docker-requirements.txt

# Make port 8000 available to the world outside this container
EXPOSE 8000

# Run web_app.py when the container launches with Gunicorn
CMD ["gunicorn", "-w", "4", "-b", "0.0.0.0:8000", "web_app:app"]

