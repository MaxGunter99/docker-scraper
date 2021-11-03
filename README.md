
# Getting Docker Running
```bash
sudo docker ps
```

this should output:
```bash
maxgunter@Maxs-MacBook-Air Docker % docker run -d -p 80:80 docker  
bcb3c035627cb15463b7a49816affebd71851e13d5fd594e4d2c802cc11e6659
maxgunter@Maxs-MacBook-Air Docker % sudo docker ps 
Password:
CONTAINER ID   IMAGE           COMMAND                  CREATED         STATUS              PORTS     NAMES
c861bf6ab5c8   docker:latest   "docker-entrypoint.s…"   8 minutes ago   Up About a minute             epic_matsumoto
maxgunter@Maxs-MacBook-Air Docker %   
```