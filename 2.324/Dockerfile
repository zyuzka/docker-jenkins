FROM jenkins/jenkins:2.324-jdk11

USER root

ENV JAVA_OPTS='-Djenkins.install.runSetupWizard=false -Xms128m -Xmx128m'

RUN apt update && \
    apt install -y \
    docker \
    netcat

RUN jenkins-plugin-cli --plugins strict-crumb-issuer:2.1.0

USER jenkins
