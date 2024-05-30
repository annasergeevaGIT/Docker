# Dockerfile
# Start from the Ubuntu 22.04 base image
FROM ubuntu:22.04

# Update the package list and install curl
RUN apt-get update && apt-get install -y curl

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the script.sh into the working directory
COPY script.sh .

# Give execution permissions to the script
RUN chmod +x script.sh

# Set the script.sh to run on container start
CMD ./script.sh


