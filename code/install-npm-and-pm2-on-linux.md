---
description: Need help setting up NodeJS & PM2 on a Linux server? Don't worry, it's easy.
---

# ⚡ Install NPM & PM2 On Linux

## Dependencies

**Curl**: `sudo apt install curl -y`

## Install NVM/NPM

`curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash`&#x20;

`source ~/.bashrc`&#x20;

`nvm install 18.8.0`

## Install  PM2 &  Setup

### Install

`npm install -g pm2`

### Setup

`pm2 start index.js --name "name"`

`pm2 save`

## Credit

Special thanks to [LunaDevv ](https://lunish.nl/)for the original source code.
