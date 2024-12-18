# Nginx - Node.js development server on Docker.

To track file changes on Windows, the project needs to be run on WSL.

## After building, you will get:

- Ubuntu
- Nginx
- Node.js
- Express
- PostgreSQL
- SSH

## Links:

- http://localhost:881/
- http://localhost:881/static/ - for static files
- SSH: ssh -p 882 root@127.0.0.1 - password: root123

## Build:

```shell
sudo docker build -t todojs_server ./backend/image
```

```shell
sudo make build
```

```shell
sudo make del
```

```shell
sudo make rebuild
```