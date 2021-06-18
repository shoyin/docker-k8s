Docker



# 卸载旧版本

```
yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine
```

# 需要的安装包

```
yum install -y yum-utils
```





# 设置镜像仓库

```
yum-config-manager \--add-repo \https://download.docker.com/linux/centos/docker-ce.repo (外网)
    
yum-config-manager \--add-repo \http://mirrors.aliyun.com/docker-ce/linux/centos/docker-ce.repo(阿里云)
```



# 安装相关 docker-ce社区有



```
yum install docker-ce docker-ce-cli containerd.io
```



# 启动

```
systemctl start docker

查看 版本
docker version
```



# Hello-World

```
docker run hello-world
```

![image-20210616111258977](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210616111258977.png)



# 查看镜像

```
docker images
```



# 卸载docker

```
yum remove docker-ce docker-ce-cli containerd.io

删除 资源
rm -rf /var/lib/docker

rm -rf /var/lib/containerd
```



