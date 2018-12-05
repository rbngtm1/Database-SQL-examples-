## SQL Queries that makes life easier
#### Create Database
      Create database if not exists task1;
#### Create Customers table
      Create table if not exists customers
      (
      cust_id int(10),
      cust_name varchar(10),
      cust_DOB varchar(10),
      );
#### Create orders table
      Create table if not exists orders
      ( 
      order_id int(10),
      order_qty int(10),
      order_date varchar(10),
      cust_id int(10)
      );
#### 
     
      
