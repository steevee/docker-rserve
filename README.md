docker-rserve
=============
1) Build: 
docker build --no-cache -t steevee/rserve:latest .
or
docker build -t steevee/rserve:latest .

2) Run:
docker run -d -p 6311:6311 --name rserve steevee/rserve:latest

3) Have a look:
docker exec -ti rserve /bin/bash



