# cuda8gl
This repository is almost the same as [nvdia/cudagl](https://hub.docker.com/r/nvidia/cudagl/), but provide the CUDA8.0 devel environment for deveolpers.

Extends the `ubuntu:16.04` image by adding opengl, glvnd and cuda 8.0. This makes opengl (i.e. `glxgears` and `gazebo`) work from any docker environment when used with nvidia-docker2, https://github.com/NVIDIA/nvidia-docker.

The reason for creating this repo is to fix the issue that `nvidia-docker2` does'nt support GLX currently on Ubuntu16.04.
Some discusses for this issue could be found at [here](https://github.com/NVIDIA/nvidia-docker/issues/534)

## dockerhub
https://hub.docker.com/r/ianre657/cuda8gl/