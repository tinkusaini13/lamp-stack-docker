# lamp-stack-docker
LAMP stack is used for building and delivering web-based applications. Its flexibility and efficiency allow smaller developers to compete with commercial software development solutions. The four components of LAMP were picked as optimal solutions for developers who wish to host, serve and manage web-based content.

***************************************************
setup latest version of mysql and phpmyadmin before setup docker and docker-compose

refer this url and setup docker

https://docs.docker.com/engine/install/

after docker setup then setup docker-compose follow some steps

 yum install git  python39 -y
 pip3 install docker-compose -y


 clone the repository

 git clone https://github.com/tinkusaini13/lamp-stack-docker.git

 cd lamp-stack-docker/
 mv lamp-stack-new-version.yml  docker-compose.yml
 docker-compose up -d
 docker ps
 
see the container is running and login the phpmyadmin using your host ip with 8080 port


************************************************************************************************************************

you need old mysql or phpmyadmin versions then use following files:

![image](https://user-images.githubusercontent.com/88707521/155122424-c143be01-a59d-44ef-871f-3afc28ad1d09.png)

 
 




