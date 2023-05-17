FROM node:20.0.0-bullseye

#
# Install utilities.
#
RUN apt update && \
    apt install -y \
        locales \
        git vim curl jq && \
    apt clean && rm -rf /var/lib/apt/lists/*

#
# # Locale = C.UTF-8
# Locale = ja_JP.UTF-8
#
# RUN locale-gen ja_JP.UTF-8 && \
#     localedef -f UTF-8 -i ja_JP ja_JP.UTF-8
# ENV LANG C.UTF-8
ENV LANG ja_JP.UTF-8

USER node
