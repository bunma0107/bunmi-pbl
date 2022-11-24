(STEP 3) PROJECT 1: LAMP STACK IMPLEMENTATION
Step 1: Installing Apache
sudo apt install apache2
![image](https://user-images.githubusercontent.com/113097621/203736978-7de293bc-52ec-4735-82ff-23b2c3fa81d0.png)
sudo systemctl status apache2
![image](https://user-images.githubusercontent.com/113097621/203737199-274cdfda-17fa-436e-8798-d85acb5fefae.png)
curl http://localhost:80
![image](https://user-images.githubusercontent.com/113097621/203739326-a63ee7bf-0fb5-4f0b-9e28-714210dbcdc7.png)
![image](https://user-images.githubusercontent.com/113097621/203739969-ec400b57-730f-40ef-b7c2-421be008f76d.png)

Step 2 — Installing MySQL
![image](https://user-images.githubusercontent.com/113097621/203741799-cadc9ded-3933-424c-8e46-392e91a6681d.png)
sudo mysql
![image](https://user-images.githubusercontent.com/113097621/203742591-5670d16d-bfda-4310-bfc9-ab2d974648a2.png)
![image](https://user-images.githubusercontent.com/113097621/203743089-bf51466a-959b-4716-9caf-3e6f9b3f6c95.png)
Start the interactive script by running:

$ sudo mysql_secure_installation

$ sudo mysql -p
![image](https://user-images.githubusercontent.com/113097621/203823105-f58ea563-13d5-42d9-8dc7-86096d1465d8.png)

Step 3 — Installing PHP

![image](https://user-images.githubusercontent.com/113097621/203824175-7c82cc50-bc19-4baf-8693-9b536069b3e9.png)
 php -v
 ![image](https://user-images.githubusercontent.com/113097621/203824619-cf0d6d19-43c9-4574-a4f1-0a613cea7b1d.png)
 
 Step 4 — Creating a Virtual Host for your Website using Apache
 sudo mkdir /var/www/projectlamp
 ![image](https://user-images.githubusercontent.com/113097621/203825030-40645cc2-9bb9-4f26-93eb-baf9f2d84730.png)

sudo chown -R $USER:$USER /var/www/projectlamp
![image](https://user-images.githubusercontent.com/113097621/203825313-c373ce5f-d5e4-4045-b6a7-659534f69eaf.png)


create and open a new configuration file in Apache’s
sudo vi /etc/apache2/sites-available/projectlamp.conf

![image](https://user-images.githubusercontent.com/113097621/203825951-709543d6-c7f0-4865-a81a-06b022d0ba88.png)

To show the new file in the sites-available directory
![image](https://user-images.githubusercontent.com/113097621/203826512-ff5ecd27-00c8-4905-8897-367dc4dc0aad.png)

To enable the new virtual host:
![image](https://user-images.githubusercontent.com/113097621/203826804-4e7a4ea1-bcb8-485e-a40a-5f10d209b4a1.png)

website URL using IP address
![image](https://user-images.githubusercontent.com/113097621/203828032-2e73111f-f8a6-46be-8248-184fba925d0e.png)

Step 5 — Enable PHP on the website

![image](https://user-images.githubusercontent.com/113097621/203829847-078d19cb-7d9d-4bf0-a32e-122c71809167.png)






![image](https://user-images.githubusercontent.com/113097621/203826308-deb41b1d-8b8f-47b4-b199-c37d944452f2.png)

 


