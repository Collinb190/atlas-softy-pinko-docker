# Use the latest ubuntu image.
FROM ubuntu:latest

# Update APT using apt-get update and install dependences.
RUN apt-get update  && \
    apt-get upgrade -y && \
    apt-get install -y python3 python3-pip && \
    pip3 install Flask

# Set the command to run when the container starts.
CMD [ "/bin/echo", "Hello, World!" ]
