

# Docker 安装

###### 安装必要的系统工具

```
yum install -y yum-utils device-mapper-persistent-data lvm2
```

###### 添加软件源

```
yum-config-manager --add-repo http://mirrors.aliyun.com/docker-ce/linux/centos/docker-ce.repo
```

###### 更新yum缓存

```
yum makecache fast
```

###### 安装Docker-ce

```
yum -y install docker-ce
```

###### 启动Docker服务

```
systemctl start docker
```

###### 运行docker hello-world

```
docker run hello-world
```