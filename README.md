# NVIDIA DinD (Docker in Docker) Container

Based on https://github.com/ehfd/nvidia-dind

Isolated DinD (Docker in Docker) container for developing and deploying Docker containers using NVIDIA GPUs and the NVIDIA container toolkit

Host is required to have the NVIDIA container toolkit installed and set up. Privileged mode is required like any other DinD container with root requirement.

```
docker run --gpus 1 -it --privileged koyeb/nvidia-dind:latest
```
