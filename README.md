# precios_locos_web

flask_app.py -> listens on 0.0.0.0 TCP/ 8000

1) Login to Docker Hub

docker login -u "<username>" -p "<password>" docker.io

2) Pull latest docker container

docker pull m6t6ng6/precios_locos_web_lite:latest

3) Run docker for this container in the target machine as a daemon

docker run --rm --name precios_locos_web -d -p 80:8000 m6t6ng6/precios_locos_web_lite