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
#### Insert statement
      Insert into task1.customers
      values (001, 'Ram', '1992May18', 'Male'), (002, 'Sita', '1992May20', 'Male');

      Insert into task1.customers values
	(002, 'Hary', '1992May18', 'Male'),
	(003, 'Tim', '1992May18', 'Male'),
	(004, 'Cherry', '1992May18', 'Male'),
	(005, 'Mary', '1992May18', 'Male'),
	(006, 'Json', '1992May14', 'Male'),
	(007, 'Kat', '1992May18', 'Male'),
	(008, 'Wilmore', '1992May15', 'Male'),
	(011, 'Jeneffer', '1992May18', 'Male');

     
      
      Insert into  task1.orders values
      (001, 01, '2018May22', 2),
      (002, 02, '2018May13', 4),
      (003, 03, '2018May24', 33),
      (004, 05, '2018May25', 11),
      (005, 06, '2018May25', 10);

