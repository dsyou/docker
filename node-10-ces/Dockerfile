FROM maven:3.6.3-openjdk-11

RUN echo "# Installing Nodejs" && \
    curl -sL https://deb.nodesource.com/setup_10.x | bash - && \
    apt-get install nodejs build-essential -y && \
    npm set strict-ssl false && \
    npm install -g npm@latest && \
    npm cache clear -f && \
    npm install -g n && \
    n stable*
