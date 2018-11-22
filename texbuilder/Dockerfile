FROM debian:stretch-slim
LABEL MAINTAINER "Chomba Ng'ang'a <choeringa@gmail.com>"
RUN apt-get update && \
    apt-get install -y biber latexmk make texlive-full poppler-utils && \
    rm -rf /var/lib/apt/lists/*
