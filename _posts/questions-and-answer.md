---
title: questions and answer
date: 2018-10-25 19:28:04
tags:
---

### questions

1. nginx split dynamic & static
```
    静态资源服务器一般用nginx
```
```
server {
   listen       80;
   server_name  localhost;
   location / {
       root   html;
       index  index.html index.htm;
   }
   location /image/ {
       root   /usr/local/myImage/;
       autoindex on;
   }

}
```

2. api gateway and cors

![](questions-and-answer/markdown-img-paste-20181027105906307.png)


3. apigateway websockets route

4. microservice and MQ load balance

4. docker && httpServer
```
    docker 只会占用一点点的cpu & memory .
    网络可能会有开销 , 默认网络模式是:bridge , 修改为host 可以直接使用native network
```
6. hexo d

7. http socket ? long tcp
