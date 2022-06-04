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
| cmake-format          |         |

## Usage

[Cpp dev with amd64](https://hub.docker.com/layers/cpp-dev/yangliz5/cpp-dev/2.0.1-amd64/images/sha256-6e59ba34da195e464e6217351cdbc54c2fb85a7f9734ffe16f432a225ee92a08?context=repo)

```console

$ docker pull yangliz5/cpp-dev:2.1.0-amd64
$ docker run -it yangliz5/cpp-dev:2.1.0--amd64 /bin/bash
$ echo $CC 
gcc
$ echo $CXX
g++
```

[Cpp dev with arm64](https://hub.docker.com/layers/227559855/yangliz5/cpp-dev/2.2.0-arm64/images/sha256-232e05a218581a778ddad3f2b63d4cf34c4deabc62c90fb80f0f9a565e366cac?context=repo)

```console
$ docker pull yangliz5/cpp-dev:2.2.0-arm64
$ docker run -it yangliz5/cpp-dev:2.2.0--amd64 /bin/bash
$ echo $CC 
clang 
$ echo $CXX
clang++
```

[Cpp dev with arm64](https://hub.docker.com/layers/217541410/yangliz5/cpp-dev/2.1.0-arm64/images/sha256-b37802fc03cf07720c9e8a786879557fb16fabd41545c9d2c9cfc115469ebd83?context=repo)

```console
$ docker pull yangliz5/cpp-dev:2.1.0-arm64
$ docker run -it yangliz5/cpp-dev:2.1.0--amd64 /bin/bash
$ echo $CC 
gcc 
$ echo $CXX
g++
```


## Acknowledgement


1. https://github.com/cpp-best-practices/gui_starter_template
