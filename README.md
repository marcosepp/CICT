# CICT

![CI status](https://github.com/marcosepp/CICT/actions/workflows/main.yml/badge.svg)

This project is created to automate the CICT (Cyber Intelligence Collection Tool) deployment. 

Repository has two subprojects [CICT client](https://github.com/ClevenL/cict-client-public) and [CICT server](https://github.com/ClevenL/cict-server-public).

To clone this repository use git clone --submodules command:

```
git clone --recurse-submodules https://github.com/marcosepp/CICT.git
```

# Use

### DockerHub containers

Steps:

1. Clone repository
> `$ git clone https://github.com/marcosepp/CICT.git`
2. Run Docker compose
>```
> $ cd CICT/
> $ docker-compose up
>```

### Build your own

Steps:

1. Clone repository
> `$ git clone --recurse-submodules https://github.com/marcosepp/CICT.git`
2. Run Docker compose
>```
> $ cd CICT/
> $ docker-compose -f docker-compose-build.yml up 
>```

### Development

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
