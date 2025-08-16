# FROM ubuntu:24.04
FROM mcr.microsoft.com/devcontainers/base:noble

RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get update && apt-get install -y python3
RUN apt-get update && apt-get install -y python3-pip

RUN apt-get update && apt-get install -y graphviz

RUN apt-get install -y python3-matplotlib
RUN apt-get install -y python3-numpy
RUN apt-get install -y python3-pandas
RUN apt-get install -y python3-graphviz
RUN apt-get install -y python3-ipykernel
