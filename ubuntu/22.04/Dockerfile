# syntax = docker/dockerfile:1
FROM ubuntu:22.04

RUN apt-get update && \
  apt-get upgrade -y && \
  apt-get purge --auto-remove && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/*
