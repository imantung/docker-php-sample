# docker-php-sample

A simple PHP web application example for [Docker's PHP Language Guide](https://docs.docker.com/language/php/).

```bash
echo "password" > db/password.txt         # create secret for password

docker compose up --build

open http://localhost:9000/hello.php      # hello world
open http://localhost:9000/info.php       # php/server info
open http://localhost:9000/database.php   # add/view message table 

open http://localhost:8080/               # phpmyadmin; username = root
```

