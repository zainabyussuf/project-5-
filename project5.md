# PROJECT 5 DOCUMENTATION 
`'sudo apt update`

`sudo apt install mysql_server`

`sudo apt install mysql_client`

*open port 3306 on mysql_server*


note:i did mysql installation on my server

created a native user and a test database

`sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`

*change the to 0.0.0.0*

*from mysql client connect to mysql server with the ip address of mysql server*

`sudo mysql -u remote_user -h(private IP)

![mysql](./images/mysql%20client.PNG)

*show databses*

![database](./images/mysql%20database.PNG)





