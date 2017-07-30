SymfonyApp - Docker
===

## Installation

1. Clone repository: 

```git clone git@github.com:radol91/symfony-docker-template.git symfony-project```

2. Copy files _.env.dist_ and _.docker-compose.yml.dist_ and adjust them for your needs:

```cp .env.dist .env && cp docker-compose.yml.dist docker-compose.yml```

3, Add line to your _/etc/hosts_ file:

```127.0.0.1   symfony-template.local```

4. Move to project directory and run command:

```docker-compose up -d```

5. Enjoy your new project working on docker on:

```http://symfony-template.local/```


## Configuration

1. You can change default `symfony-template.local` address in _docker-compose.yml_:

```
environment:
        - VIRTUAL_HOST=symfony-template.local
```
