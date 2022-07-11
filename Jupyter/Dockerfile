FROM jupyter/minimal-notebook:aarch64-latest
USER root
RUN apt update && apt -y install make g++ && rm -rf /var/lib/apt/lists/*
RUN npm install -g --unsafe-perm ijavascript
RUN ijsinstall --install=global
RUN apt -y remove make g++
