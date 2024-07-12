# Use the latest Python image from Docker Hub
FROM python:latest
 
# Set the working directory in the container
WORKDIR /workspace
 
# Copy the current directory contents into the container at /workspace
COPY . /workspace
 
# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
