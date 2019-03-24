# DockerizedNginx

### SSL Settings
1. Add .crt certification file under ./ssl_certificate/
2. Add .key certification pirate key file under ./ssl_certificate/
3. Configure Nginx SSL settings on ./nginx_conf/ssl.conf

### Update Domain Name
On various Nginx configuration files under ./nginx_conf/,
replace `hamkuu.com` with designated & certified domain name.

### Spinning Up with Docker
```
$ docker-compose build --no-cache
$ docker-compose up -d

```
