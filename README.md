# docker-images
cd a2typo3 <br />
docker build -t a2typo3 .  <br />
docker run -dit -p 8080:80 a2typo3 /usr/sbin/apache2ctl -D FOREGROUND
