[![Docker Pulls](https://img.shields.io/docker/pulls/kaixhin/cuda-caffe.svg)](https://hub.docker.com/r/kaixhin/cuda-caffe/)
[![Docker Stars](https://img.shields.io/docker/stars/kaixhin/cuda-caffe.svg)](https://hub.docker.com/r/kaixhin/cuda-caffe/)

cuda-caffe
==========
Ubuntu Core 14.04 + [CUDA 6.5](http://www.nvidia.com/object/cuda_home_new.html) + [Caffe](http://caffe.berkeleyvision.org/). Includes Python interface.

Requirements
------------

- [NVIDIA Docker](https://github.com/NVIDIA/nvidia-docker) - see [requirements](https://github.com/NVIDIA/nvidia-docker/wiki/CUDA#requirements) for more details.

Usage
-----
Use NVIDIA Docker: ``nvidia-docker run -it kaixhin/cuda-caffe``.

For more information on CUDA on Docker, see the [repo readme](https://github.com/Kaixhin/dockerfiles#cuda).

Citation
--------
If you find this useful in research please consider [citing this work](https://github.com/Kaixhin/dockerfiles/blob/master/CITATION.md).
