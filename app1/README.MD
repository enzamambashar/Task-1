To run the app1 from docker hub, please download or clone all the src files.

Go to deploy folder and edit the docker-compose.yml and change the volume according to /src folder

volumes:
      - '/home/enzamam/b23p/app1/src:/app'
	  
After that please run the following command to start the container

docker compose up -d