docker-php-nginx-mysql-memcached


```bash
$ cd docker-php-nginx-mysql-memcached
$ docker-compose up
```

Stop:

```bash
$ docker-compose stop
```

## Switch PHP Version 5.6

You can switch PHP version 5.6.

If you want to use PHP 5.6, write below on `docker-compose.yml`.

```diff
<    build: ./php-fpm71
>    build: ./php-fpm56
```

