FROM jenkins/jenkins:2.176.1-jdk11

USER root

ENV JAVA_OPTS='-Djenkins.install.runSetupWizard=false -Xms128m -Xmx128m'

RUN apt update && \
    apt install -y \
    docker \
    netcat

USER jenkins
