FROM mcr.microsoft.com/devcontainers/python:3.11
RUN apt-get update && apt-get install -y git make curl && rm -rf /var/lib/apt/lists/*
RUN pip install --no-cache-dir numpy scipy sympy matplotlib jupyterlab
