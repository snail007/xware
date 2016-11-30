# xware
迅雷远程下载固件（稳定版）  

1、树梅派使用的是：Xware_armel_v5te_glibc.tar.gz  

2、友善之手臂arm开发版M1使用的是：Xware_cubieboard.tar.gz

3、更多可以参考<a href="http://g.xunlei.com/thread-50-1-1.html" target="_blank">Xware 支持产品不完全列表[持续更新]</a>

#安装示例：  

 #!/bin/bash
 
tar zxfv Xware_armel_v5te_glibc.tar.gz  -C  /root/apps/xware  

cd /root/apps/xware/  

./portal >./init.log 2>&1   

cat init.log  
