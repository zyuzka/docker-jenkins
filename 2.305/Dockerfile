FROM jenkins/jenkins:2.305-jdk11

USER root

ENV DISABLE_CSRF_PROTECTION='false'
ENV JAVA_OPTS='-Djenkins.install.runSetupWizard=false -Xms128m -Xmx128m -Dhudson.security.csrf.GlobalCrumbIssuerConfiguration.DISABLE_CSRF_PROTECTION=${DISABLE_CSRF_PROTECTION}'

RUN apt update && \
    apt install -y \
    docker \
    netcat

USER jenkins
