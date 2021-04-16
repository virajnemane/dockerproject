docker build -t virajnemane/mynginx:v1 --build-arg tag=1.18 --build-arg message="This is viraj nginx server" .
docker push virajnemane/mynginx:v1
docker run -itd -p 80:80 virajnemane/mynginx:v1

Output from host system
root@ip-10-21-150-114:~/proj/task2# curl localhost:80
This is viraj nginx server
