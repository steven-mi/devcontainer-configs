# Use the specified Python image as a parent image
FROM mcr.microsoft.com/devcontainers/python:1-3.12

# Install Node.js
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash - \
    && apt-get install -y nodejs \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*


RUN pip install --upgrade pip
RUN pip install poetry
