# xware
迅雷远程下载固件（稳定版）  

1、树梅派使用的是：Xware_armel_v5te_glibc.tar.gz  

2、友善之手臂arm开发版M1使用的是：Xware_cubieboard.tar.gz

#安装示例：  

 #!/bin/bash
 
tar zxfv Xware_armel_v5te_glibc.tar.gz  -C  /root/apps/xware  

cd /root/apps/xware/  

./portal >./init.log 2>&1   

cat init.log  
