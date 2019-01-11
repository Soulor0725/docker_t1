"# docker_t1" 
1 docker build --tag=friendlyhello .
2 docker run -p 4000:80 friendlyhello
3 curl http://localhost:4000
4 docker run -d -p 4000:80 friendlyhello 后台运行
5 docker container stop ID 停止容器
