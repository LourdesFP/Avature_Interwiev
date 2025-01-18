# FROM python:3
FROM python:3

# Set environment variables
ENV MONGO_URI=mongodb://127.0.0.1:27017
ENV MONGO_DB=restdb

# Create dir to work and set it as working directory
WORKDIR /app

#Copy and install decedencies specified in requirements.txt.
COPY requirements.txt .
RUN apt-get update -y && apt-get install -y python3-pip python3-dev
RUN pip3 install --no-cache-dir -r requirements.txt

# Copy the project source code from the local host to the filesystem of the container at the working directory.
COPY ./api .

# Command to run the application
CMD [ "python3"; "app.py"]