FROM jenkins/jenkins:2.324-jdk11

USER root

ENV JAVA_OPTS='-Djenkins.install.runSetupWizard=false -Xms128m -Xmx128m -Dhudson.security.csrf.GlobalCrumbIssuerConfiguration.DISABLE_CSRF_PROTECTION=false'

RUN apt update && \
    apt install -y \
    docker \
    netcat

USER jenkins
