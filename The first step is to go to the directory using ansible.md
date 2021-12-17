The first step is to go to the directory using ansible

![image-20211217174646436](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217174646436.png)

The next step is install packages with ansible

![image-20211217174709763](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217174709763.png)

Create e config.yml file

![image-20211217174819167](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217174819167.png)

Do the installation using the script below

![image-20211217174954163](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217174954163.png)

Add subdomain to /etc/hosts

![image-20211217175009922](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175009922.png)

Open vm.local file

![image-20211217175054065](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175054065.png)

Add line [www](http://www/). After that exit lxc

![image-20211217175439436](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175439436.png)

Open and edit vm.local in directory /etc/nginx/sites-enabled/

![image-20211217175458743](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175458743.png)

![image-20211217175522547](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175522547.png)

Open and edit vm.local in directory /etc/bind/vm/

![image-20211217175550158](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175550158.png)

![image-20211217175554716](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175554716.png)

Restart

Sudo service bind9 restart

Sudo sercive nginx restart

Sudo /etc/init.d/named restart

 

Setting konektifitas 

![image-20211217175628083](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175628083.png)

![image-20211217175635623](C:\Users\WAHID\AppData\Roaming\Typora\typora-user-images\image-20211217175635623.png)