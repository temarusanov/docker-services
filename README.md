
# Docker services

Docker services allow you to start postgres, rabbitMQ, redis, adminer using one command. The main point of this project is to create one folder where all the services launched on the servers will be stored.




## Features

- All services in one file
- Configuration for all services
- Volume store in this repository

## Services

- PostgreSQL
- Adminer
- RabbitMQ
- Redis
  
## Installation

Create folder

```bash
mkdir ~/docker
```

Clone this repo

```bash
git clone https://github.com/temarusanov/docker-services.git .
```

Run containers

```bash
docker-comspose up -d
```
    
## Default ports

 - Adminer: 8080
 - PostgreSQL: 5432
 - RabbiMQ: 5672 & 15672
 - Redis: 6379

  
