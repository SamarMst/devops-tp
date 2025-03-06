# Use Python 3.9 image as the base image
FROM python:3.9

# Copy the content of the hello-devops directory to the /app directory inside the container
COPY hello-devops/ /app

# Set the working directory to /app
WORKDIR /app

# Install the necessary Python packages from requirements.txt
RUN pip install -r requirements.txt

# Set the default command to run the app
CMD ["python", "app.py"]
