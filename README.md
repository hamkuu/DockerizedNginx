# DockerizedNginx

### Get a .key File
The private key is generated simultaneously with the CSR (certificate signing request), containing the domain name, public key and additional contact information.

### SSL Settings
1. Add .crt certification file under ./ssl_certificate/
2. Add .key certification pirate key file under ./ssl_certificate/
3. Configure Nginx SSL settings on ./nginx_conf/ssl.conf

### Update Domain Name
On various Nginx configuration files under ./nginx_conf/,
replace `DOMAIN_NAME` with designated & certified domain name.

### Spinning Up Containers
```
$ docker-compose build --no-cache
$ docker-compose up -d
```
