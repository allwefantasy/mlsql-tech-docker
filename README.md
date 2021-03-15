# MLSQL.TECH docker项目

只需把编译好的前端项目拷贝到html即可。

## 构建镜像：

```
docker build -t mlsql-tech .
```

## 启动命令

```
docker run  --name mlsql-tech-site -p 8080:80 -d mlsql-tech
```