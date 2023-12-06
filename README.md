# jsp_servlet_mysql_curd-project
JSP SERVLET MYSQL CURD AJAX JAVASCRIPT

CREATE DATABASE 'users';
USE users;

create table customer(
 id  int(3) NOT NULL AUTO_INCREMENT,
 name varchar(120) NOT NULL,
 email varchar(220) NOT NULL,
 phone varchar(10) NOT NULL,
 username vatchar(10) NOT NULL,
 password varchar(8) NOT NULL,
 PRIMARY KEY (id)
);
