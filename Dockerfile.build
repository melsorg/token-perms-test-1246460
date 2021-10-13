#
# Ubuntu Dockerfile
#
# https://github.com/dockerfile/ubuntu
#

# Pull base image.
FROM ubuntu:18.04

# Add and change user.

RUN useradd --shell /bin/bash --create-home cicd-runner
USER cicd-runner

# Define default command.
CMD ["bash"]
