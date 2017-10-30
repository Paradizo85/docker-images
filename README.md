# docker-images
cd a2typo3
docker build -t a2typo3 .
docker run -dit -p 8080:80 a2typo3 /usr/sbin/apache2ctl -D FOREGROUND
