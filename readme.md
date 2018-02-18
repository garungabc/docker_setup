#### Docker tool
##### ====== khoi dong docker ======
docker-compose up
docker-compose up -d : de tra ket qua ve terminal hien tai chu khong tra ve terminal trong docker

##### ====== Tat docker ========
docker-composer down

##### ===== Kiem tra xem package nao dang hoat dong ======
docker-compose ps

##### ====== truy cap ssh den project =======
winpty docker exec -it nginx bash

##### ====== Xoa tat ca cac Container =======
docker rm -f $(docker ps -aq)

##### ====== Lay thong tin env tu Machine ======
docker-machine env

##### ====== Tao env tai thu muc can den =======
eval $("C:\Program Files\Docker Toolbox\docker-machine.exe" env)

##### ====== remove may ao trong virtualbox ======
docker-machine rm {ten may ao}: docker-machine rm default

##### ====== start - stop machine ===============
docker-machine stop default
docker-machine start default

