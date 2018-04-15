# A React App - Todo List example

## Requirements
- Docker Compose
- Yarn

## Installation for the codebase

0. Install the node_modules for the API and App projects:
```
cd api && yarn
cd ..
cd app && yarn
cd ..
```

1. create ALL the Docker containers:
```
yarn dev:install
```

## Start the docker composed development environment

2. Run the project
```
yarn dev:up
```

and then visit the WebSite:
[localhost:8000](http://localhost:8000)

3. Stopping the Project
```
yarn dev:down
```

4. Installing ther servers (clean down)
```
yarn dev:uninstall
```
