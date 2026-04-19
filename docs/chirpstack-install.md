# ChirpStack Install (Real Guide)

## Tested Host OS

- Ubuntu 22.04 LTS

## Update System

sudo apt update
sudo apt upgrade -y

## Install Docker

sudo apt install -y docker.io docker-compose-plugin
sudo systemctl enable docker
sudo systemctl start docker

## Create Project Folder

mkdir ~/chirpstack
cd ~/chirpstack

## Download Example Compose Files

Use the official ChirpStack docker-compose example for:

- ChirpStack
- PostgreSQL
- Redis
- Mosquitto MQTT

## Start Stack

docker compose up -d

## Verify Containers

docker ps

## Access Web Interface

Default web UI is typically available on port 8080.

http://SERVER_IP:8080

## Notes

Change default credentials immediately.
Review the official ChirpStack version documentation.
