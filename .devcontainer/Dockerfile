FROM python:3.10-slim

RUN apt-get update && apt-get install -y \
    curl wget git htop nano unzip \
    && rm -rf /var/lib/apt/lists/*

RUN pip install flask

RUN useradd -m vscode
USER vscode
WORKDIR /home/vscode
