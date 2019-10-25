### 1. build前端镜像
```
docker build -t aria2-frontend .
```
### 2. build后端镜像
```
docker build -t aria2-backend .
```
### 3. 利用docker-compose启动
```
docker-compose up -d
```
### 4. 默认下载目录在项目根目录下downloads目录
