# Nombre del repo

Descripcion del repo

Explicacion de como lanzar la aplicacion

# Gunicorn
```
$ gunicorn --chdir src app:app -bind 0.0.0.0:5000
```

# Docker
```
$ docker build -t user/devops
$ docker run -d -p 80:5000 --name devops2 user/devops
```

# Compose
```
docker compose up -d
```