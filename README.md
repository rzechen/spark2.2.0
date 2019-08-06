# Desc
install single spark2.2.0

# Pull images

```
docker pull registry.cn-hangzhou.aliyuncs.com/ranzechen/spark2.2.0:latest
```

# Run Command
  
```
# make a container
docker run -itd --name spark2.2.0 -p 192.168.145.128:17077:7077 -p 192.168.145.128:18080:8080 awsterra/spark2.2.0:latest /bin/bash
# enter container spark2.2.0
docker exec -it a7670f11fce8 /bin/bash
# in spark2.2.0 start master and worker
```
