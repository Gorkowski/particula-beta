FROM mcr.microsoft.com/devcontainers/python:3.13

COPY . /workspaces/template/
RUN pip3 --disable-pip-version-check --no-cache-dir install -e "/workspaces/template/[dev]"
