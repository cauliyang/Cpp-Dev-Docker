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
| :---------------------| ------- |
| Clang++               | 13.0    |
| Clang                 | 13.0    |
| Gcc                   | 11.0    |
| G++                   | 11.0    |
| Clang-tidy            | 13.0       |
| Clang-format          | 13.0       |
| conan                 | 1.46        |
| python                | 3.8     |
| cmake                 | 3.22        |
| include-what-you-want | 0.17        |
| cppcheck              | 1.90       |
| cmake-format          |         |

## Container in DockerHub

[Cpp dev with amd64](https://hub.docker.com/repository/docker/yangliz5/cpp-dev)

```console

$ docker pull yangliz5/cpp-dev:2.0.1-amd64

```

[Cpp dev with arm64](https://hub.docker.com/repository/docker/yangliz5/cpp-dev)

```console
$ docker pull yangliz5/cpp-dev:2.0.1-arm64

```

