# Docker-JRebel-License-Server
Docker image for running a JRebel License Server

## Usage
Run with ```docker run -p 9000:9000 -v data:/jrebel/license-server/data --mac-address=MACADDRESS cgoit/jrebel-license-server```

Be sure you specify the mac address. This can be the same as your physical netword device. This avoid the server to ask for activation each time the container is restarted.

Follow the activation procedures http://zeroturnaround.com/software/license-server/quick-start/#!/activation

Based on official java:8 image

## Using docker compose

Just run docker-compose up -d in the same directory the included docker-compose.yml resides.
