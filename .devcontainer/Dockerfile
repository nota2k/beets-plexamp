FROM mcr.microsoft.com/devcontainers/base:bullseye

RUN apt-get update && \
    apt-get install -y \
    python3-pip

RUN pip install beets
RUN pip install "beets[discogs]"
RUN pip install "beets[fetchart]"
RUN pip install "beets[plugins]"
RUN pip install beetcamp