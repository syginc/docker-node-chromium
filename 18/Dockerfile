FROM node:18-buster

RUN apt-get update && \
    apt-get install -y chromium libgtk-3-0 fonts-noto-cjk && \
    rm -rf /var/lib/apt/lists/*

ENV CHROME_PATH /usr/bin/chromium
