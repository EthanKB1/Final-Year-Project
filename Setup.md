# TheHive and Cortex Setup Guide

## Ubuntu Desktop (TheHive)

1. Login to Ubuntu Desktop
2. Open terminal
3. Navigate to TheHive directory and start services:
   ```shell
   cd thehive
   sudo docker-compose up -d
   sudo docker ps

Access TheHive:

Open Firefox
Navigate to: http://localhost:9000
Login with: ethan@thehive.local / ethan1

Ubuntu Server (Cortex & Elasticsearch)

Login to Ubuntu Server: ethan / student1
Start Elasticsearch and Cortex:
shellcd elasticsearch
sudo docker-compose up -d
sudo docker ps

Access Cortex from Ubuntu Desktop:

Open Firefox
Navigate to: http://192.168.0.123:9001
Login with: ethanadminkatano / ethan2
