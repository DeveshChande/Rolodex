# Create a Fedora container aligned towards development and debugging of C Programs.

FROM fedora:latest

RUN dnf update -y && dnf install -y gcc make gdb git

WORKDIR /app