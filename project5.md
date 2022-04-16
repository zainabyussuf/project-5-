# PROJECT 5 DOCUMENTATION 
`'sudo apt update`

`sudo apt install mysql_server`

`sudo apt install mysql_client`

*open port 3306 on mysql_server*

`sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`

*change the to 0.0.0.0*

*from mysql server connect to mysqlclient with the ip address of mysql server*

`sudo mysql -u remote_user -h(private IP)

![mysql](./images/mysql%20client.PNG)

*show databses*

![database](./images/mysql%20database.PNG)





