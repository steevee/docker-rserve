docker-rserve
=============
1) Build: 
docker build --no-cache -t rserver/test1 .
or
docker build -t rserver/test1 .

2) Run:
docker run -d -p 6311:6311 --name rserv1 rserver/test1

3) Have a look:
docker exec -ti rserv1 /bin/bash



