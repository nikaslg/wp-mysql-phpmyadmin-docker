# wp-mysql-phpmyadmin-docker
a very primitive docker-compose.yml file to help me develop wordpress sites on wordpress 

Create project folder wherever you want.</br>
INSIDE PROJECT FOLDER create folder named code where your actual wordpress code will be held and clone the docker-compose.yml file, best to git clone it otherwise watch the spaces.(Otherwise change the folder name inside the docker-compose file)</br>
in your terminal navigate to your project folder</br>
run -> docker-compose up -d</br>
chown -R USER:GROUP code/</br>
And then you can move your files into the wordpress dir</br>
</br>
To stop the containers</br>
docker-compose down</br>
</br>
To remove the containers</br>
docker-compose down --volumes</br>
</br>
If you change something</br>
docker-compose up -d --build</br>
</br>
To check the logs</br>
docker-compose logs -f</br>
</br>
http://localhost:8000 <--your wordpress</br>
http://localhost:9191 <--phpmyadmin to manipulate your databases</br>
</br>
phpmyadmin details:</br>
root
somewordpress</br>
</br>
wordpress</br>
wordpress</br>
