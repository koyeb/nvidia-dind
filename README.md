# NVIDIA DinD (Docker in Docker) Container

Based on https://github.com/ehfd/nvidia-dind

Isolated DinD (Docker in Docker) container for developing and deploying Docker containers using NVIDIA GPUs and the NVIDIA container toolkit

Host is required to have the NVIDIA container toolkit installed and set up. Privileged mode is required like any other DinD container with root requirement.

```
docker run --gpus 1 -it --privileged koyeb/nvidia-dind:latest
```

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=nvidia-dind&type=docker&image=koyeb%2Fnvidia-dind&privileged=true&service_type=worker&instance_type=gpu-nvidia-rtx-4000-sff-ada&env%5B%5D=&ports=8000%3Bhttp%3B%2F)
