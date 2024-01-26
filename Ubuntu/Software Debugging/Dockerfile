# Create an Ubuntu container aligned towards development and debugging of C Programs.

FROM ubuntu:latest

# Install required packages
RUN apt update -y && apt install -y gcc make gdb git


# Download and Install pwndbg
RUN git clone https://github.com/pwndbg/pwndbg /opt/pwndbg
WORKDIR /opt/pwndbg
RUN ./setup.sh

# Download and Install pwntools
RUN pip install pwntools