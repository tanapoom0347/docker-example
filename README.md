# example-docker  
  
mysql  
docker run --rm --name some-mysql -p 3306:3306 -e MYSQL_RO
OT_PASSWORD=123456 -d mysql:latest  
ALTER USER 'root' IDENTIFIED WITH mysql_native_password BY '123456';  
  
docker log-in power-shell  
docker login -u tanapoom0347  
  
-v mssqlvolume:/var/opt/mssql กำหนด save volume  

docker run --rm --name some-nginx -p 80:80 -p 443:443 -d nginx:latest  
docker exec -it some-nginx bash  
docker cp default.conf some-nginx:/etc/nginx/conf.d  
certbot --nginx -d 100.68.118.83  
apt update  
apt install certbot python3-certbot-nginx  
nginx -s reload  
docker   
