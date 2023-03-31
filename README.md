<img src="https://raw.githubusercontent.com/colav/colav.github.io/master/img/Logo.png"/>

# colasticsearch
Colav Elastic Search Dev Ops


# Description
This package allows to setup a docker container with elasticsearch.

# Installation

# OS Prerequisite
Run the next command to increase the vm max_map_count
```bash
sudo sysctl -w vm.max_map_count=262144
```

## Dependencies
Docker and docker-compose is required.
* https://docs.docker.com/engine/install/ubuntu/ (or https://docs.docker.com/engine/install/debian/, etc)
* Install `docker-compose`:  
```bash
apt install docker-compose
```
or
```bash
pip install docker-compose
```

* https://docs.docker.com/engine/install/linux-postinstall/


# Usage

```bash
docker-compose up
``` 



**This is required to perform massive insertions in parallel!**

# License
BSD-3-Clause License 

# Links
http://colav.udea.edu.co/

