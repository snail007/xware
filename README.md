# xware
迅雷远程下载固件（稳定版）  
树梅派使用的是：Xware_armel_v5te_glibc.tar.gz  

#安装示例：  
 #!/bin/bash  
if [  -f /root/apps/xware/protal ] ; then  
         /root/apps/xware/protal -s   
         rm -rf /root/apps/xware  
fi  
if [ ! -d /root/apps/xware ] ; then  
         mkdir /root/apps/xware  
fi  
tar zxfv Xware_armel_v5te_glibc.tar.gz  -C  /root/apps/xware  
cd /root/apps/xware/  
./portal >./init.log 2>&1    
cat init.log  
