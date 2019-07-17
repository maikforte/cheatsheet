# Personal Cheatsheet

# Table of contents
1. [Design References](#design-references)
1. [Design Tools](#design-tools)
1. [Commands](#commands)
  i. [Ionic 4](#ionic-4)
  i. [Kubernetes](#kubernetes)
  i. [Heroku](#heroku)
  i. [Node](#node)
  i. [NPM](#npm)
  i. [Angular CLI](#angular-cli)
  i. [Redis](#redis)
  i. [RedisQueue](#redisqueue)
  
## Design References
- [WebFrame](https://webframe.xyz) - Discover and be inspired by beautiful webapp designs

## Design Tools
- [Lunacy](https://icons8.com/lunacy?ref=producthunt) - Sketch for Windows

## Commands

### Ionic 4
- `ionic generate <type> <name> [options]`
  - `npx ng g --help` Get list of Types
  - `npx ng g <type> --help` Get options per Type
  
### Kubernetes
- `kubectl -n <namespace> get pods`

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
