## Docker Images
This repository contain a series of Docker images that
- allow you to quickly set up your deep learning research environment
- supports GPU acceleration(CUDA and cuDNN included), also works in CPU-only mode
- works on linux(CPU version/GPU version), even the NPU version
-------------------------------
## CPU Version
### Installation
Step 1. Install [Docker](https://docs.docker.com/engine/install/).

Step 2. xxx (TODO)

Step 3. Build Docker image using the following command.

    docker build -f Dockerfile.tf1.15.0 -t image_name:tag_name .

Step 4. Push the built Docker image to Docker Hub or [SWR](https://www.huaweicloud.com/product/swr.html)

    docker push image_name:tag_name

## GPU Version
### Installation
Step 1. Install [Docker](https://docs.docker.com/engine/install/) and [nvidia-docker](https://github.com/NVIDIA/nvidia-docker).

Step 2. xxx (TODO)

Step 3. Build Docker image using the following command. 

    docker build -f Dockerfile.tf1.15.0-gpu -t image_name:tag_name .

Step 4. Push the built Docker image to Docker Hub or [SWR](https://www.huaweicloud.com/product/swr.html)

    docker push image_name:tag_name

## ModelArts NPU Version
### Installation
Step 1. Install [Docker](https://docs.docker.com/engine/install/).

Step 2. xxx (TODO)

Step 3. Build Docker image using the following command. More details you can refer to the [wiki](https://gitee.com/echo_lin/modelzoo/wikis/ModelArts%E8%87%AA%E5%AE%9A%E4%B9%89NPU%E8%AE%AD%E7%BB%83%E7%8E%AF%E5%A2%83%E9%95%9C%E5%83%8F%E6%89%8B%E5%86%8C%E3%80%90%E5%9F%BA%E7%A1%80%E7%89%88%E3%80%91?sort_id=3541942#%E5%85%AC%E5%85%B1%E9%95%9C%E5%83%8F%E7%9A%84%E5%88%B6%E4%BD%9C).

    docker build -f Dockerfile.modelarts -t image_name:tag_name .

Step 4. Push the built Docker image to Docker Hub or [SWR](https://www.huaweicloud.com/product/swr.html)

    docker push image_name:tag_name
