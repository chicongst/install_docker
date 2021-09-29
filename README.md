# Install Docker
```
sudo apt-get update
sudo apt-get install curl
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
```
```
sudo groupadd docker
sudo usermod -aG docker $USER
newgrp docker
```
```
sudo service docker start
```

# Install Docker Compose
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```
```
docker-compose --version
```
