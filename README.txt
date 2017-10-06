This is a double server configuration with a persistant database.

Config
	-2 nginx servers to host applications
	-2 custum php7:fpm servers (for modularity)
	-1 mariadb server
	-1 busybox for database persistance

Lanch the project

First clone the project:
	git clone git@github.com:cnerot/docker_project.git

To Launch App 1
	docker-compose -f app1.yml up -d

To Launch App 2
	docker-compose -f app2.yml up -d

To Launch App 1 & 2
	docker-compose -f app12.yml up -d
