# 离线安装zabbix-docker
 * 首先确保你有一个zabbix.tar的镜像文件 
 * 启动方式
      >桥接方式直接启动
      >host方式启动
      
    
  *启动代码(bridge)
  ```
  #docker run -d -it   
   -p 10051:10051 \
   -p 10080:80    \
   -v /var/lib/mysql           /var/lib/zabbix
      /etc/zabbix/alert        /etc/zabbix/alert
      
   -name zabbix  wuyujie_zabbix:lastest  /usr/sbin/init 
  ```
  
  
