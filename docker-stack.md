### Docker Swarm init
```bash
  docker swarm init --advertise-addr <your_ip: port>
```

### Create attachable network 

```bash 
  docker network create -d overlay --attachable <any_name>
```

### pullimages
```bash 
  ./pullimages
```

### Run Images with docker stack
```bash
  docker stack deploy -c docker-compose.yml nest
```

### Vew all running images in service
```bash 
  docker stack services <service_name>
```

### Remove Docker service
```bash 
  docker stack rm <service_name>
```


### Join different network
```bash
  docker swarm join --token <your_token> <your_ip:port>
```
