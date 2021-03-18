Repo dari https://github.com/soft-industry/docker-compose-php

semua setingan di pindah ke folder docker agar lebih dikit
--
web
localhost:8080 //port bebas

mysql
backup di docker/mysql
--
nginx
pengaturan ada di  docker/nginx/conf.d

log ada di docker/log

-----------------------------------------------------

runing

copy docker-compose.yml // sesuai versi
copy php-fpm //sesuai versi

ke root folder

seting agar mengarah ke folder docker.

docker-compose build
docker-compose up -d