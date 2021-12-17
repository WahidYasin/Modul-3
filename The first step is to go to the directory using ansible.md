The first step is to go to the directory using ansible
![image](https://user-images.githubusercontent.com/95128942/146534728-f32a95db-f602-4838-ba72-0873b749b232.png)


The next step is install packages with ansible

![image](https://user-images.githubusercontent.com/95128942/146535209-cb821e82-276f-4bc0-b73d-94d50de8b044.png)

Create e config.yml file
![image](https://user-images.githubusercontent.com/95128942/146535244-7cbbf14f-3a9d-461d-967c-99c5edc238ca.png)

Do the installation using the script below
![image](https://user-images.githubusercontent.com/95128942/146535407-b60d85d7-729f-419e-a4ac-989238923cbe.png)

Add subdomain to /etc/hosts
![image](https://user-images.githubusercontent.com/95128942/146535413-8bec9453-5ec7-4146-997a-e2318b836e49.png)

Open vm.local file
![image](https://user-images.githubusercontent.com/95128942/146535432-829399cf-93e5-4ae2-ace6-76b6f0e9b8fc.png)


Add line [www](http://www/). After that exit lxc
![image](https://user-images.githubusercontent.com/95128942/146535455-4ca88624-4705-4be5-ac53-7d20c3c6a837.png)


Open and edit vm.local in directory /etc/nginx/sites-enabled/
![image](https://user-images.githubusercontent.com/95128942/146535469-cf355b7f-e91b-4324-ac70-cc1c660c5c65.png)
![image](https://user-images.githubusercontent.com/95128942/146535474-d6aee16e-2375-446b-98c7-df7fe026cdbd.png)

Open and edit vm.local in directory /etc/bind/vm/
![image](https://user-images.githubusercontent.com/95128942/146535487-fa79fb30-76c3-4817-a931-7d71f358b22f.png)

![image](https://user-images.githubusercontent.com/95128942/146535501-9ebbe9a8-625c-4729-9772-c04d54ac06ec.png)

Restart

Sudo service bind9 restart

Sudo sercive nginx restart

Sudo /etc/init.d/named restart


 

Setting konektifitas

![image](https://user-images.githubusercontent.com/95128942/146535771-3acb9f16-9304-4552-b2a6-d51e202e6d80.png)
![image](https://user-images.githubusercontent.com/95128942/146535790-5405c400-de8a-47f9-aa01-9dab85dc1617.png)
