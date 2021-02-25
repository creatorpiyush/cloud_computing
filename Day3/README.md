## File System

```
touch   p1   p2     p3    p4

ls   -lrt   p*

chmod    123   p1

ls  -lrt   p1

chmod   546   p1

ls  -lrt   p1

chmod   763   p1

ls  -lrt   p1

chmod  531  p1

ls  -lrt   p1

chmod  247 p1

ls  -lrt   p1
```

## Create DB in aws connect

```
> mysql_secure_installation
> mysql -u root -p
> create database testdb;
> create user 'testuser1'@'localhost' identified by 'B@RIM143s';
> grant all privileges on testdb.* to 'testuser1'@'localhost';
root# mysql -u testuser1 -p use testdb;
> create table customers (customer_id INT NOT NULL AUTO_INCREMENT PRIMARY KEY, first_name TEXT, last_name TEXT);
> desc customers;
```
