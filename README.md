# Acme-Script
基于Acme的一键申请证书脚本

直接在命令行运行即可，根据提示选择

泛域名证书使用CloudFlare API申请，需要域名在CF（推荐把域名放到cf，因为各种功能非常方便）

```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/senqi77/Acme-Script/main/acme.sh && bash acme.sh
```

优化了保存证书逻辑，在每个域名申请证书时都会单独创建文件夹保存证书，方便整理
