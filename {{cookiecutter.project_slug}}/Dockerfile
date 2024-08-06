FROM python:{{ cookiecutter.python_version }}-slim-bullseye

WORKDIR /workspace

# Install dependencies
RUN apt update && \
    apt install -y curl build-essential openssh-client zip unzip tmux && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*

# Install UV
RUN curl -LsSf https://astral.sh/uv/install.sh | sh

ENV UV_SYSTEM_PYTHON=1
ENV PATH="/root/.cargo/bin/:$PATH"
