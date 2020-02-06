# Personal Cheatsheet

# Table of contents
1. [Design References](#design-references)
1. [Design Tools](#design-tools)
1. [Mobile App Testing Tools](#mobile-app-testing-tools)
1. [Icons](#icons)
1. [Miscellaneous](#miscellaneous)
1. [Commands](#commands)
    1. [Ionic 4](#ionic-4)
    1. [Kubernetes](#kubernetes)
    1. [Docker](#docker)
    1. [Heroku](#heroku)
    1. [Node](#node)
    1. [NPM](#npm)
    1. [Angular CLI](#angular-cli)
    1. [Redis](#redis)
    1. [RedisQueue](#redisqueue)
  
## Design References
- [WebFrame](https://webframe.xyz) - Discover and be inspired by beautiful webapp designs

## Design Tools
- [Lunacy](https://icons8.com/lunacy?ref=producthunt) - Sketch for Windows
- [RemoveBackground](https://www.remove.bg) - Automatically removes the background from the photo
- [Coolors](https://coolors.co) - Color Palette Generator

## Mobile App Testing Tools
- [Appium](http://appium.io)
- [Robotium](https://github.com/robotiumtech/robotium)
- [Selendroid](http://selendroid.io)

## Icons
- [Feather Icons](https://feathericons.com)

## Miscellaneous
- [Checklist](https://www.checklist.design) - Common checklist for common pages
- [Carrd](https://carrd.co) - Create single page
- [Crello](https://crello.com) - Social Media Post Templating
- [Hygger](https://hygger.io) - Product Management Tool

## Commands

### Ionic 4
- `ionic generate <type> <name> [options]`
  - `npx ng g --help` List Types
  - `npx ng g <type> --help` Get options per Type
  
### Kubernetes
- `kubectl -n <namespace> get pods` List pods
- `kubectl logs -n <namespace> <pod_name> -f` Show pod logs
- `kubectl exec -it -n <name_space> <pod_name> -- /bin/bash` SSH into pod

### Docker
- `docker image ls` List images
- `docker image prune` Cleans up unused image(s)
- `docker image rm <image_id>` Removes an image
- `docker ps` List running containers
- `docker kill <container_id>` Kills running container(s)
- `docker build <project_path>` Builds a docker image
    - `docker image build -t <image_tag> <project_path>` Builds a docker image with tag
- `docker container run <image_tag>` Runs a Docker container from the image
    - `docker container run --publish <host_port>:<container_port> <image_tag>` Runs a Docker container forwarding all traffic from host port to container port
    - `... --name <container_name>` Runs a Docker container while specifying a container name
- `docker-compose up` Run series of Docker containers declared in `docker-compose.yml`

### Heroku
- `heroku apps` List the Apps of current Heroku user
- `heroku logs -a <app_name>` Displays the log for certain app
  - `--tail` To tail log
  
### Node
- `node -v` Get Node version

### NPM
- `npm --v` Get NPM version

### Angular CLI
- `ng new <project_name>` Creates new project within the folder
- `ng generate component <directory>/componentName` Generates Angular component (in `/app` folder)
- `ng generate service <directory>/serviceName` Generates Angular service (in `/app` folder)

### Redis
- `redis-server` Stars the RedisServer

### RedisQueue
- `rqworker` Starts the RedisQueue worker
