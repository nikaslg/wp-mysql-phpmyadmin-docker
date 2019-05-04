# wp-mysql-phpmyadmin-docker
a very primitive docker-compose.yml file to help me develop wordpress sites on wordpress 

You just copy the file.
Create project folder
INSIDE PROJECT FOLDER create folder named code(Otherwise change the folder name inside the docker-compose file)
in your terminal navigate to your project folder
run -> docker-compose up -d
chown -R USER:GROUP code/
And then you can move your files into the wordpress dir

To stop the containers
docker-compose down

To remove the containers
docker-compose down --volumes

If you change something
docker-compose up -d --build

To check the logs
docker-compose logs -f

http://localhost:8000 <--your wordpress
http://localhost:9191 <--phpmyadmin to manipulate your databases

phpmyadmin details:
root
somewordpress

wordpress
wordpress
