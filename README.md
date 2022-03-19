# Cpp-Dev-Docker

Docker Image for cpp development in different architecture

## Dockerfiles

### File Structure

Dockerfiles
├── Dockerfile
└── cmake-3.19-Dockerfile

### Tools in container

| Tool                  | Version |
| --------------------- | ------- |
| Clang++               | 13.0    |
| Clang                 | 13.0    |
| Gcc                   | 11.0    |
| G++                   | 11.0    |
| Clang-tidy            |         |
| Clang-format          |         |
| conan                 |         |
| python                | 3.8     |
| cmake                 |         |
| include-what-you-want |         |
| cppcheck              |         |
| cmake-format          |         |

## Container in DockerHub

[Cpp dev with cmake-3.19 aarch64](https://hub.docker.com/repository/docker/yangliz5/cpp-dev-cmake3.19)

```console

docker push yangliz5/cpp-dev-cmake3.19:tagname

```

[Cpp dev with amd64](https://hub.docker.com/repository/docker/yangliz5/cpp-dev-amd64)

```console

docker push yangliz5/cpp-dev-amd64:tagname

```
