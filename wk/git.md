1.进入某一目录，Linux直接用命令行，Windows右键使用“Git Bash Here”

2.配置一个用于提交代码的用户，输入指令：

    git config --global user.name "shoyin"

同时配置一个用户的邮箱，输入命令：

```
git config --global user.email "hoyin_vip@163.com"
```

3.生成公钥和私钥（用于github）

``` 
ssh-keygen -t rsa -C "hoyin_vip@163.com"
```

