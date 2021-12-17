
# Docker services

Docker services allow you to start services using one command. The main point of this project is to create one folder where all the services launched on the servers will be stored.




## Features

- All services in one file
- Configuration for all services
- Volume store in this repository

## Services

- PostgreSQL
- Adminer
- RabbitMQ
- Redis
- MongoDB
- MongoExpress
  
## Installation

1. Create folder

```bash
mkdir ~/docker
```

2. Clone this repo

```bash
git clone https://github.com/temarusanov/docker-services.git .
```

3. Create `.env` from `.env.example` and configure it

4. Run containers

```bash
docker-comspose up -d
```

Or launch specific containers

```bash
docker-compose up -d adminer postgres
```
    
## Default ports

 - Adminer: 8080
 - PostgreSQL: 5432
 - RabbiMQ: 5672 & 15672
 - Redis: 6379
 - MongoDB: 27017-27019
 - MongoExpress: 8081

  
