# TheHive and Cortex Setup Guide

## Ubuntu Desktop (TheHive)

1. Login to Ubuntu Desktop
2. Open terminal
3. Navigate to TheHive directory and start services:
   ```shell
   cd thehive
   sudo docker-compose up -d
   sudo docker ps

### Access TheHive:

Open Firefox
Navigate to: 

```
http://localhost:9000
```
Login with: 
```
ethan@thehive.local / [contact repository owner for credentials]
```
### Ubuntu Server (Cortex & Elasticsearch)

Login to Ubuntu Server: 
```
ethan / [contact repository owner for credentials]
```
Start Elasticsearch and Cortex:
```shell
cd elasticsearch
sudo docker-compose up -d
sudo docker ps
```
Access Cortex from Ubuntu Desktop:

Open Firefox
Navigate to: 
```
http://192.168.0.123:9001
```
Login with: 
```
ethanadminkatano / [contact repository owner for credentials]
```
