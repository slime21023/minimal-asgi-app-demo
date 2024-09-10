# Docker compose as a systemd unit

Create file `/etc/systemd/system/asgi-app.service`
* Install `docker`, `docker-compose` by ubuntu snap


## Start the service

```bash
systemctl start asgi-app.service
```

## Stop the service
```bash
systemctl stop asgi-app.service
```

## Enable the service

```bash
systemctl enable asgi-app.service
```

## Default Application Path 

path: `/etc/app-service/mini-asgi-app`