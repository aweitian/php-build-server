# php-build-server
php build-in server with rewrite

## 使用方法
- 如果项目目录不是WEB根目录,使用public下两个文件,将它们复制到项目根目录,将bat和php文件中的public换成web目录名

- 如果项目目录是WEB根目录,复制本目录下bat和php文件到项目根目录.

## 启动HTTP服务
双击startSvr.bat

## 访问地址
http://127.0.0.1

## 修改端口
> php -S 127.0.0.1:80 -t . server.php
> 修改其中的80
