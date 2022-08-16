# Cpp-Dev-Docker

![Docker Automated build][docker build]
![Docker Image Size (latest by date)][docker image-size]
![Docker Stars][docker starts]
![Docker Image Version (latest by date)][docker image version]

[docker image version]: https://img.shields.io/docker/v/yangliz5/cpp-dev?style=for-the-badge
[docker starts]: https://img.shields.io/docker/stars/yangliz5/cpp-dev?style=for-the-badge
[docker image-size]: https://img.shields.io/docker/image-size/yangliz5/cpp-dev?style=for-the-badge
[docker build]: https://img.shields.io/docker/automated/yangliz5/cpp-dev?style=for-the-badge

Docker Image for C++ development in different architecture

## File Structure

```
Dockerfiles
├── Dockerfile
└── cmake-3.19-Dockerfile
```

## Tools in container

| Tool                  | Version |
| :-------------------- | ------- |
| Clang++               | 13.0    |
| Clang                 | 13.0    |
| Gcc                   | 11.0    |
| G++                   | 11.0    |
| Clang-tidy            | 13.0    |
| Clang-format          | 13.0    |
| conan                 | 1.46    |
| python                | 3.8     |
| cmake                 | 3.22    |
| include-what-you-want | 0.17    |
| cppcheck              | 1.90    |
| cmake-format          | 0.6.13  |

## Usage

[Cpp dev with amd64 gcc](https://hub.docker.com/layers/cpp-dev/yangliz5/cpp-dev/2.0.1-amd64/images/sha256-6e59ba34da195e464e6217351cdbc54c2fb85a7f9734ffe16f432a225ee92a08?context=repo)

```console

$ docker pull yangliz5/cpp-dev:2.1.0-amd64
$ docker run -it yangliz5/cpp-dev:2.1.0--amd64 /bin/bash
$ echo $CC 
gcc
$ echo $CXX
g++
```

[Cpp dev with arm64 clang](https://hub.docker.com/layers/cpp-dev/yangliz5/cpp-dev/2.2.1-arm64/images/sha256-3b72e323a60bef6f5577ccc5d7c75d01ace7a6b48cb1df2b0776a05e87eac560?context=repo)

```console
$ docker pull yangliz5/cpp-dev:2.2.1-arm64
$ docker run -it yangliz5/cpp-dev:2.2.1--amd64 /bin/bash
$ echo $CC 
clang 
$ echo $CXX
clang++
```

[Cpp dev with arm64 gcc](https://hub.docker.com/layers/cpp-dev/yangliz5/cpp-dev/2.3.1-arm64/images/sha256-0b879edd834119cf2ff6b353974ed336cf19f240723e03d19c4175edb8e0ed79?context=repo)

```console
$ docker pull yangliz5/cpp-dev:2.3.1-arm64
$ docker run -it yangliz5/cpp-dev:2.3.1--amd64 /bin/bash
$ echo $CC 
gcc 
$ echo $CXX
g++
```


## Acknowledgement


1. https://github.com/cpp-best-practices/gui_starter_template
