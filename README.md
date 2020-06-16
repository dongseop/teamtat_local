# TeamTat Local

You can run TeamTat(https://teamtat.org) server on your local machine.

## How to

1. Install Docker (https://docs.docker.com/get-docker/)
2. Install git (https://git-scm.com/)
3. clone this repository (or download this repository)
  ```
  git clone git@github.com:dongseop/teamtat_local.git
  ```
4. change directory into teamtat_local
  ```
  cd teamtat_local
  ```
5. run the server by using `docker-compose up`
  ```
  docker-compose up
  ```
6. If you have errors while starting the 'web' container, please stop all containers using 'Ctrl+C' and retry it.
  ```
  docker-compose up
  ```  
  For the first time starting the server, the 'web' container may fail to start because of the dependency to the 'db' container. Then, you should stop all containers and start it again. Sorry.

You can access the server from http://localhost:3000

To change the port or other settings, please look into docker-compose.yml


