# angular-template
## create a new application
```
$ docker-compose up --detach
$ docker-compose exec --user 0 angular /bin/sh
> cd ~/
> npm install -g @angular/cli
> exit
$ docker-compose exec angular /bin/sh
> cd ~/
> ng new my-app
> exit
```

## serve the application
```
$ docker-compose up --detach
$ docker-compose exec angular ng serve --host 0.0.0.0
```
