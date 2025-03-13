FROM jenkins/jenkins:lts

USER root

# Update package lists and install required dependencies
RUN apt-get update && \
    apt-get install -y --no-install-recommends make g++ && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

USER jenkins
