# Docker Git Server

This repository contains the files necessary to create a Git server using Docker. 

You can start the server by running `docker compose up -d`. Then you can create new repositories by running `docker-compose exec git-server mkrepo repo-name`.
Finally, you are able to clone the repo by running `git clone http://localhost:8080/repo-name.git`.
