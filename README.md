# CICT

![CI status](https://github.com/marcosepp/CICT/actions/workflows/main.yml/badge.svg)
![GitHub](https://img.shields.io/github/license/marcosepp/CICT)


| CICT client | CICT server |
|-|-|
| ![Docker Pulls](https://img.shields.io/docker/pulls/marcosepp/cict-client) <br> ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/marcosepp/cict-client/latest) | ![Docker Pulls](https://img.shields.io/docker/pulls/marcosepp/cict-server) <br> ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/marcosepp/cict-server/latest) |
| ![GitHub repo size](https://img.shields.io/github/repo-size/ClevenL/cict-client-public) | ![GitHub repo size](https://img.shields.io/github/repo-size/ClevenL/cict-server-public) |


This project is created to automate the CICT (Cyber Intelligence Collection Tool) deployment. 

Repository has two subprojects [CICT client](https://github.com/ClevenL/cict-client-public) and [CICT server](https://github.com/ClevenL/cict-server-public).

To clone this repository use git clone --submodules command:

```
git clone --recurse-submodules https://github.com/marcosepp/CICT.git
```

# Use

### DockerHub containers

You can use pre-build Docker containers from Docker Hub.

Steps:

1. Clone repository
> `$ git clone https://github.com/marcosepp/CICT.git`
2. Run Docker compose
>```
> $ cd CICT/
> $ docker-compose up
>```

### Build your own

You can build your own containers.

Steps:

1. Clone repository
> `$ git clone --recurse-submodules https://github.com/marcosepp/CICT.git`
2. Run Docker compose
>```
> $ cd CICT/
> $ docker-compose -f docker-compose-build.yml up 
>```

### Development

You can use Node dev environment and skip Nginx

Steps:

1. Clone repository
> `$ git clone --recurse-submodules https://github.com/marcosepp/CICT.git`
2. Run Docker compose
>```
> $ cd CICT/
> $ docker-compose -f docker-compose-dev.yml up 
>```


# Author

Marco Sepp

# Licence

MIT