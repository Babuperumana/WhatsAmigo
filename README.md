# WhatsAmigo - api
![WhatsAmigo-api](https://github.com/Babuperumana/WhatsAmigo/static/master/static/media/zapzap-api.png?raw=true)

This project is based on the [Venom-bot](https://github.com/orkestral/venom), a virtual browser without a graphical interface that opens whatsapp web and executes all commands via code, thus enabling the automation of all functions.

## Setup:

`sudo apt install -y gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget build-essential apt-transport-https libgbm-dev`
- to install all necessary dependencies on the system

`curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -`

`sudo apt install git nodejs yarn`
- To install git, nodejs e yarn

`git clone https://github.com/cleitonleonel/zapzap-api.git`

`cd WhatsAmigo`

`npm install`

`npm init -y`

`npm cache verify`

`npm i --save-dev`

`npm i venom-bot`

`cp .env-example .env`

### If there are errors when starting, manually install:

`sudo apt-get update`
`sudo apt-get install -y libgbm-dev`

### Starting the server:

`node index.js`

### Keeping processes active with each server restart:

`npm install pm2 -g`

`pm2 start index.js`

`pm2 startup`

## Usage
- Register and login in the system, after that you will be redirected to the following screen:

  <img src="https://github.com/Babuperumana/WhatsAmigo/master/static/media/qrcode_read.png?raw=true" width="400">

- Siga as instruções na tela e se abrirá uma tela de testes como essa:

  <img src="https://github.com/Babuperumana/WhatsAmigo/master/static/media/send_message.png?raw=true" width="400">


- Test as much as you like if you like our service and want to hire us send an email to [babuperumana@gmail.com](babuperumana@gmail.com)

## To install certbot and create the SSL certificate for https domains:
  
```shell script
sudo apt-get update && sudo apt-get install -y software-properties-common

sudo add-apt-repository universe && sudo add-apt-repository ppa:certbot/certbot

sudo apt-get update && sudo apt-get install -y certbot

sudo certbot certonly --manual --force-renewal -d *.yourdomain.net -d yourdomain.net --agree-tos --no-bootstrap --manual-public-ip-logging-ok --preferred-challenges dns-01 --server https://acme-v02.api.letsencrypt.org/directory
```

# Did this project help you?

If this project lets you feel free to make a donation =), it can be R $ 0.50 hahahaha. For that, just read the qrcode below, it was generated with my other project called [Pypix](https://github.com/cleitonleonel/pypix.git) sample file.

![QRCode Doação](https://github.com/cleitonleonel/pypix/blob/master/qrcode.png?raw=true)


# Developed by:

Babu Perumana ==> babuperumana@gmail.com
