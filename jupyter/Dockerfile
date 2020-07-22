FROM jupyter/scipy-notebook
USER jovyan
RUN pip install jupyter_dashboards
USER root
RUN apt-get update && apt-get upgrade -y apt-transport-https
RUN apt-get install openjdk-11-jdk -y
RUN apt-get install 