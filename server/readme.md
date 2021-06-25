1. 构建docker镜像

```
docker build -t mediasoup:1.0 .
```

2. 运行docker容器

```
docker run -it --rm --net=host mediasoup:1.0
```

   

