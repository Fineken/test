FROM jenkins/jenkins:lts

USER root 

RUN apt update && apt install -y python3 python3-pip python3-venv
RUN python3 -m venv /venv
RUN /venv/bin/pip install pytest pytest-cov allure-pytest


USER jenkins
