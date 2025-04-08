# LAMP-Starter
This repository runs a LAMP container [link](https://github.com/mattrayner/docker-lamp) for PHP and MySQL development.

Run `./startDocker.sh` in the terminal to start the container.
The container uses three folders:
- /app - This is the root serving folder for the Apache web server.  Put HTML, PHP, and any other files here for your web application.
- /mysql - This folder will be created if it doesn't already exist.  The MySQL server will store all data files here and fill it if empty.  Deleting this folder and restarting the container deletes all data in the databse.
- /logs - This folder will be created if it doesn't already exist.  The Apache web server's log files will be saved here, useful in debugging PHP code.
