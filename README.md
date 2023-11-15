# Ebook App stack
Based on the work done by [https://www.linuxserver.io/]
uses the calibre and web_caliber images and assumes you already have a download stack setup and ready to go.

Pull repo

`git clone https://github.com/billsardine/ebook-appstack.git`

Copy the .env.example file to .env

`cp .env.example .env`

Change the variables in the .env file to appropriate values

Start the container in the console to verify settings

`sudo sudo docker-compose up`

Kill the container and start it in the background

`sudo sudo docker-compose up -d`