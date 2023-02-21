#https://blog.logrocket.com/building-simple-login-form-node-js/#registering-user

`sudo  mysql -u root -p`

`create database logindb;`

```
USE logindb
CREATE TABLE users (
     id SMALLINT NOT NULL AUTO_INCREMENT,
     name varchar(100) NOT NULL,
     email varchar(100) NOT NULL ,
     password varchar(200) NOT NULL,
     PRIMARY KEY (id)
);

```
