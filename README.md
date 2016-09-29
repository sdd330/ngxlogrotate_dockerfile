# Nginx Docker Image supports Log Rotation
------------
Docker image for a simple nginx web server with logrotate functionality

Usage
------------

To start an instance:

	docker run -d --name nginx-with-logrotate sdd330/ngxlogrotate

To login to bash:

	docker exec -it nginx-with-logrotate bash
