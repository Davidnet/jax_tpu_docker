# Jax TPU VM Docker 

## Run Docker Container
```bash
sudo docker run --net=host --privileged -it --entrypoint=/bin/bash orenleung/jax_tpu:latest
```

## Build Docker Image
```bash
sudo docker build -t orenleung/jax_tpu .
```