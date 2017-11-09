# docker-images

Typo3
cd a2typo3 <br />
docker build -t a2typo3 .  <br />
docker run -dit -p 8080:80 a2typo3 /usr/sbin/apache2ctl -D FOREGROUND

Lavarel 
cd lavarel <br />
docker build -t lavarel .  <br />
docker run --rm -it -p 443:443 -p 80:80 -v <PATH>:/var/www/html lavarel:latest
