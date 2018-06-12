# notes on docker-machine

## create a docker-machine node

```bash
docker-machine create \                                                                                                                          7:08:49
  -d generic \
  --generic-ip-address 1.2.3.4 \
  --generic-ssh-key "$HOME/.ssh/KEYNAME" \
  --generic-ssh-port "22" \
  --generic-ssh-user "ubuntu" \
  --engine-insecure-registry insecure.registry:5000 \
  DOCKER_MACHINE_NAME
```  
