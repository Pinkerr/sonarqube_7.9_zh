# sonarqube_7.9 中文版docker-compose 安装

## 拉取代码
```git clone https://github.com/Pinkerr/sonarqube_7.9_zh.git```


## 创建目录并授予777权限
```cd sonarqube_7.9_zh```

```mkdir -p postgres/{postgresql,data} sonarqube/{logs,data,conf}```

```chmod -R 777 postgres sonarqube```


## 启动docker-compose
```docker-compose up -d```


## 网页登录 
ip:9000

默认用户名密码：admin/admin
