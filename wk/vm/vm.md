```apache
BOOTPROTO=static        #开机协议，有dhcp及static；
ONBOOT=yes              #设置为开机启动；
DNS1=114.114.114.114    #这个是国内的DNS地址，是固定的；
IPADDR=192.168.3.204      #你想要设置的固定IP，理论上192.168.2.2-255之间都可以，请自行验证；
NETMASK=255.255.255.0   #子网掩码，不需要修改；
GATEWAY=192.168.3.1 



BOOTPROTO=static        
ONBOOT=yes              
DNS1=114.114.114.114    
IPADDR=192.168.3.204      
NETMASK=255.255.255.0   
GATEWAY=192.168.3.1 


service network restart
```