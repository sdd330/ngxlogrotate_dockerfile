# Nginx Docker Image supports Log Rotation
------------
Docker image for a simple nginx web server with logrotate functionality

Usage
------------

To start an instance:

	docker run -d --name nginx-with-logrotate -v <your-web-dir>:/www -p 443:443 sdd330/ngxlogrotate

To login to bash:

	docker exec -it nginx-with-logrotate bash
