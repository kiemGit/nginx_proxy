enable firewall 

    sudo ufw enable
  	sudo ufw allow 22/tcp
  	sudo ufw allow 80/tcp
  	sudo ufw allow 443/tcp
  	sudo ufw allow 3003/tcp
  	sudo reboot now

create directory

    mkdir nginx-docker && cd nginx-docker

build docker container

    docker-compose up -d

open browser 

    http://192.168.0.22   //for local
    http://gdsap.work.gd  //for public


