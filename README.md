# Personal Cheatsheet

# Table of contents
1. [Ionic 4](#ionic-4)
1. [Kubernetes](#kubernetes)
1. [Heroku](#heroku)
1. [Node](#node)
1. [NPM](#npm)
1. [Angular CLI](#angular-cli)
1. [Redis](#redis)
1. [RedisQueue](#redisqueue)

## Ionic 4
- `ionic generate <type> <name> [options]`
  - `npx ng g --help` Get list of Types
  - `npx ng g <type> --help` Get options per Type
  
## Kubernetes
- `kubectl -n <namespace> get pods`

## Heroku
- `heroku apps` List the Apps of current Heroku user
- `heroku logs -a <app_name>` Displays the log for certain app
  - `--tail` To tail log
  
## Node
- `node -v` Get Node version

## NPM
- `npm --v` Get NPM version

## Angular CLI
- `ng new <project_name>` Creates new project within the folder
- `ng generate component <directory>/componentName` Generates Angular component (in `/app` folder)
- `ng generate service <directory>/serviceName` Generates Angular service (in `/app` folder)

## Redis
- `redis-server` Stars the RedisServer

## RedisQueue
- `rqworker` Starts the RedisQueue worker
