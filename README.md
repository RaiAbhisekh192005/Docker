fist install the updates
```
sudo apt update -y
sudo apt install docker.io -y
```

check if docker is installed and running 
```
sudo systemctl status docker 
```

update the user setting
```
sudo usermod -aG docker ubuntu
```

make sure to restart the system before runnning docke commands

