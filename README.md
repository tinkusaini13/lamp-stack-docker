# lamp-stack-docker
LAMP stack is used for building and delivering web-based applications. Its flexibility and efficiency allow smaller developers to compete with commercial software development solutions. The four components of LAMP were picked as optimal solutions for developers who wish to host, serve and manage web-based content.

********************************************************************************************************************************************************************************
Setup latest version of mysql and phpmyadmin before setup docker and docker-compose

refer this url and setup docker

https://docs.docker.com/engine/install/

After docker setup then setup docker-compose follow some steps

 yum install git  python39 -y
 
 pip3 install docker-compose -y


 clone the repository

 git clone https://github.com/tinkusaini13/lamp-stack-docker.git

 cd lamp-stack-docker
 
 mv lamp-stack-new-version.yml  docker-compose.yml
 
 docker-compose up -d
 
 docker ps
 
 
 ![image](https://user-images.githubusercontent.com/88707521/155124670-9005c987-ab92-4513-9aa5-ef66446b8cd3.png)


 
see the container is running and login the phpmyadmin using your host ip with 8082 port

Example : 192.168.1.128:8082


![image](https://user-images.githubusercontent.com/88707521/155125137-4402c0c4-d176-4a43-9cb9-4b58918b6660.png)



***************************************************************************************************************************************************************************
  mysql or phpmyadmin other versions are docker-compose file available into this repository see: ***************************************************************************************************************************************************************************
 
 ![image](https://user-images.githubusercontent.com/88707521/155122830-13919a3f-463c-48b1-8a20-d504aa306350.png)

Some case login phpmyadmin ask username with  password then check the docker-compose  file you have use.defualt username is root

username : root  
password: : MYSQL_ROOT_PASSWORD

Like 

![image](https://user-images.githubusercontent.com/88707521/155127504-5a007c4f-72d8-4352-bac2-c563a7150039.png)



mysql version 5.6  phpmyadmin version 5.1.1

 https://github.com/tinkusaini13/lamp-stack-docker/blob/main/lamp-stack-v1.yml
 
 
mysql version 5.7  phpmyadmin version 5.0

https://github.com/tinkusaini13/lamp-stack-docker/blob/main/lamp-stack-v2.yml


mysql version 8.0  phpmyadmin version 5.1.3

https://github.com/tinkusaini13/lamp-stack-docker/blob/main/lamp-stack-v3.yml

mysql version 5.6  phpmyadmin version 5.0

https://github.com/tinkusaini13/lamp-stack-docker/blob/main/lamp-stack-v4.yml


mysql version 5.5  phpmyadmin version 5.0

https://github.com/tinkusaini13/lamp-stack-docker/blob/main/lamp-stack-v5.yml


 
 




