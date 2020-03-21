

---
Add project.test to /etc/hosts, e.g.:

`127.0.0.1 localhost project.test`

https://github.com/chriszarate/docker-compose-wordpress

docker-compose run --rm wp-cli wp [command]

docker-compose run --rm wp-cli wp --info

Install:
docker-compose run --rm wp-cli install-wp
(is executed in wp-cli container, runs bin/install-wp.sh script  > can be edited to add users)


Permissions:

`docker-compose run --rm wordpress chown -R www-data:www-data /var/www/html/wp-content`


---
"docker-compose down" wieder mit "docker-compose up --build"
-


