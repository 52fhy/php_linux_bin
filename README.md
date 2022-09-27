# php_linux_bin


php7，php8 Linux二进制版本，已打包部分扩展，便于快速部署。提取自[phpstudy](https://www.xp.cn/linux.html)。

二进制包详见 https://github.com/52fhy/php_linux_bin/releases/tag/v1.0

安装：
``` bash
./install
```

如果已经安装了php，需要先卸载或者：
``` bash
sudo /usr/bin/php /usr/bin/php.bak
```


相关命令：
``` bash
php-fpm
php-fpm stop

php -m
php --ri swoole
```

支持pecl安装：
```
sudo pecl install https://pecl.php.net/get/grpc-1.44.0.tgz
```
