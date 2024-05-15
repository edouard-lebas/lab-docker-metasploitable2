# Lab Metasploitable2 under docker
This lab is intended for pentest training. Everything is portable and can be set up in a few minutes in Docker.

## First Run

````shell
docker-compose build
````
````shell
docker-compose up -d
````

## Exploit
````shell
docker exec -it KALI /bin/bash
````
````shell
docker exec -it METASPLOITABLE /bin/sh
````

## Install app on kali

````shell
apt update
````
````shell
apt install nmap hydra sqlmap metasploit-framework ftp
````
