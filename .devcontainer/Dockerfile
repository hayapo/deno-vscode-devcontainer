FROM mcr.microsoft.com/vscode/devcontainers/base:bullseye

RUN apt-get update && \
  apt-get install -y curl unzip

RUN curl -fsSL https://deno.land/x/install/install.sh | sh

WORKDIR /workspace

EXPOSE 8080

USER vscode