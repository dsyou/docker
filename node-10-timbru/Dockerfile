FROM maven:3.6.3-openjdk-11

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - \
  && apt-get update -qq \
  && apt-get install -qq --no-install-recommends \
    nodejs \
  && apt-get upgrade -qq \
  && rm -rf /var/lib/apt/lists/*
