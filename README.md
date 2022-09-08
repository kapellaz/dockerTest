##DockerTest

-Usefull commands:

  -Install docker:
  ```console
    sudo apt install docker.io docker-compose -y
  ```
  Create a docker-compose file:
  ```console
    sudo nano docker-compose.yaml
  ```
  Show the containers created:
  ```console
    sudo docker-compose ps
  ```
  Launch a docker-compose file:
  ```console
    sudo docker-compose up -d  (-d means Detached mode or ,in other words, run containers in the background)
  ```
  Shut down a docker-compose stack:
  ```console
    sudo docker-compose down
  ```
    
  Stop a docker-compose stack:
  ```console
    sudo docker-compose stop
  ```
  To run a specific container see the containers created (with command mencioned above) and type:
  ```console
    sudo docker exec -it $name bash
  ```
  
