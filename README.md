# docker-mosquitto-service

This is a little repo that lets me run mosquitto on a Raspberry Pi on boot at low effort.

## Usage
0. `sudo apt install docker-compose`
1. Clone this repo to your pi
2. `sudo cp docker-mosquitto-service.service /etc/systemd/system/docker-mosquitto-service.service`
3. `sudo systemctl enable docker-mosquitto-service.service`
