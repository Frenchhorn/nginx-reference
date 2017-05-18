# nginx-reference

## 安装
### Windows
>http://nginx.org/en/download.html
### Linux
`apt-get install nginx`

## 基本操作
* 启动
>直接执行文件     
`sudo service nginx start`
* 快速停止
>nginx -s stop       
`sudo service nginx stop`
* 逐渐停止
>`nginx -s quit`
* 重新加载配置文件      
>`nginx -s reload`
* 重新打开日志文件      
>`nginx -s reopen`