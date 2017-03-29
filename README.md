#使用docker 建立以adminer 為平台的mysql

啟動 docker-compose

docker-compose up -d 

adminer 存取帳密

database    : db
user        : root
password    : 12345678

使用command line 登入mysql 

docker exec -it mysql bash

#made by James
