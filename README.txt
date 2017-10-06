This is a double server configuration with a persistant database.

Config
	-2 nginx servers to host applications
	-2 custum php7:fpm servers (for modularity)
	-1 mariadb server
	-1 busybox for database persistance