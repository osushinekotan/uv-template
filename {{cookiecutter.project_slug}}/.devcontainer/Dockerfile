FROM python:3.11-slim-bookworm
COPY --from=ghcr.io/astral-sh/uv:latest /uv /bin/uv

WORKDIR /workspace

RUN apt update && \
    apt install -y curl build-essential git openssh-client zip unzip tmux && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*
