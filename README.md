### Setup

```
sudo docker-compose up -d nginx mysql workspace
```

**connect laravel vs laradock**

```
docker-compose exec mysql bash
```

```
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'root';
ALTER USER 'default'@'%' IDENTIFIED WITH mysql_native_password BY 'secret';
exit;
```

```
exit;
```

```
docker-compose exec workspace bash

cd hackathon

php artisan ...
```
