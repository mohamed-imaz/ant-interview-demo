# Use the official Python image as the base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install Flask
RUN pip install Flask

# Expose port 8080 to the outside world
EXPOSE 8080

# Command to run the Flask application
CMD ["python", "app.py"]