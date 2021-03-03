# Cheat Sheet
This repository aims at compiling any interesting and/or useful commands, suggestions, reminders and alike related to programming.
Inspired by the (much greater) [Today I learned](https://github.com/amandafbri/today-i-learned) repo from [@amandafbri](https://github.com/amandafbri).


## Linux Terminal
```bash
ssh user@remote.ip
scp /path/to/file user@remote.ip:/path/to/remote/directory/     # Copy files using SSH
scp -r /path/to/folder user@remote.ip:/path/to/remote/    # Copy directories using SSH

chmod +x /path/to/script.py        # Make script executable
ps -ef | grep '*'       # Get background processes

```

## Docker Compose
```bash
docker-compose up -d --build    # Build then run containers in detach mode
docker-compose exec service_name python script.py method_name   # Execute method from python script on specific service
docker-compose exec db_service psql --username=user_name --dbname=db_name   # Enter psql terminal at db_name using user user_name
docker-compose down -v      # Stops containers and removes volumes created by 'up'
```

## Vue.js Client
```bash
npm run serve
npm run build
```

## Google Firebase
```bash
firebase login
firebase init
firebase deploy
```