# shell 脚本命令

## 防火墙

防火墙打开端口

```shell
sudo firewall-cmd --zone=public --add-port=4001/tcp --permanent
```

防火墙重载

```shell
sudo firewall-cmd --reload
```

防火墙已经打开的端口

```shell
sudo firewall-cmd --zone=public --list-ports
```

