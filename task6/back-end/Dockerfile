# Use the latest ubuntu image.
FROM ubuntu:latest

# Update APT using apt-get update and install dependences.
RUN apt-get update  && \
    apt-get upgrade -y && \
    apt-get install -y python3 python3-pip && \
    pip3 install Flask && \
    pip3 install flask-cors

# Set the working directory in the container.
WORKDIR /app

# Copy the python file to the working directory.
COPY api.py /app/api.py

# Expose port 5252 to the outside world.
EXPOSE 5252

# Set the command to run when the container starts.
CMD [ "python3", "api.py" ]
