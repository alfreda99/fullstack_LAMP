# Lola's Bookstore
This web app demostrates the development and deployment of a full stack web application which included the configuring of a linux environment, setting up firewall and security, configuring users, installing and configuring Apache web server, intalling and configuring PostgreSQL database and developing and deploying a Python web application. The app is hosted at http://52.35.169.138:80.  The SSH port is 2200.

To run the program:
1. Setup the database by executing 'python database_setup.py'
2. Populate the database with dummy data by executing 'database_load.py'.
3. Execute the program by going to http://52.35.169.138:80


## The software installed included:
- Apache Web Server
- Apache WSGI module - configured it to hand off request to Python/Flask application, virtual host
- PostgreSQL Database - created/configured new database and database owner/role
- Git - cloned web application code for Lola's Bookstore, also updated code to work with linux environment and Postgres database
- Python
- Pip
- Flask
- SQLAlchemy
- Psycopg
- OATH2Client


## List of website used:
- https://discussions.udacity.com
- https://discussions.udacity.com/t/p5-how-i-got-through-it/15342/11
- https://discussions.udacity.com/t/project-5-resources/28343
- http://askubuntu.com
- https://help.ubuntu.com/community/ApacheMySQLPHP
- https://help.ubuntu.com/lts/serverguide/httpd.html
- https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps

