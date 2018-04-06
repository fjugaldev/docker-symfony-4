# Docker Symfony 4

Includes:
- NGINX
- PHP-FPM (PHP 7.2 - Latest)
- MariaDB
- Elasticsearch
- PHPMyAdmin

You need to navigate to infrastructure folder and run:

```
sudo docker-compose build
```

And then:

```
sudo docker-composer up -d
```

Next go to your browser and enter into:

- Webserver: http://127.0.0.1:8080
- MariaDB: localhost:8082
- PHPMyAdmin: localhost:8081

