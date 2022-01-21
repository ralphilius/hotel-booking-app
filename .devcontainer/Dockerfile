FROM cirrusci/flutter:stable

RUN sudo apt-get update -y \
    && sudo apt-get install -y gpg-agent curl software-properties-common \
    && curl -sL https://deb.nodesource.com/setup_12.x | sudo bash - \
    && sudo apt-get install -y nodejs \
    && sudo npm install -g yarn
