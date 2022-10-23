# Environment PHP with Docker

if you have a project with no frameworks, this is what you need to containerize each service.

## Steps

```
$ mkdir php8_projects

$ cd php8_projects

$ echo "<h1>Hello, world</h1>" > index.php

$ git clone git@github.com:lugabrielbueno/docker-php.git .

$ docker-compose up -d
```

Now it must be run on address _**localhost/php8_projects**_ and the phpmyadmin is on _**localhost:8080**_
