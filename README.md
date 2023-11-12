# docker-nodejs
This is a minimal template to create a Node.js Docker Development Environment. You can do this either by using Docker-Compose or Docker Dev Environments in the desktop client.

## Docker-Compose (recommended)
Clone this Repository and start the container.
```
docker-compose up -d
```

Now you can open VSCode and connect to the container via the Remote-Container extension. The directory where all the repository content gets loaded in is `/com.docker.devenvironment.code`.

## Docker Development Environments
To setup the DevEnv open Docker Desktop, go to `Dev Environments -> Create` and provide the URL to this repository. Now Docker sets up the container which you can then open in VSCode. The directory where all the repository content gets loaded in is /com.docker.devenvironment.code.
