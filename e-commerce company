create database company;
use company;
create table Employees(
emp_id int AUTO_INCREMENT UNIQUE primary key,
emp_name VARCHAR(255) NOT NULL, 
department VARCHAR(255) NOT NULL,
salary bigint, 
hire_date date
);

create table Customers(
customer_id int AUTO_INCREMENT UNIQUE primary key,
name VARCHAR(255) NOT NULL, 
country VARCHAR(255) NOT NULL
);

create table orders(
customer_id int ,
order_id int AUTO_INCREMENT UNIQUE primary key,
order_date date,
total_amount double,
FOREIGN KEY(customer_id) REFERENCES Customers(customer_id)
);


insert into Employees(emp_id,emp_name,department,salary,hire_date) values
(1,'ONE','IT',100000,'2022-01-01'),
(2,'TWO','IT',70000,'2022-03-04'),
(3,'THREE','IT',60000,'2023-01-01'),
(4,'FOUR','NON-IT',100000,'2023-01-01'),
(5,'FIVE','NON-IT',50000,'2023-05-03'),
(6,'SIX','NON-IT',10000,'2023-10-01'),
(7,'SEVEN','NON-IT',40000,'2023-11-01'),
(101, 'Alice Thompson', 'IT', 95000, '2022-03-15'),
(102, 'Bob Miller', 'NON-IT', 72000, '2021-07-22'),
(103, 'Charlie Davis', 'NON-IT', 68500, '2023-01-10'),
(104, 'Diana Prince', 'IT', 110000, '2020-11-05'),
(105, 'Evan Wright', 'NON-IT', 62000, '2022-09-28'),
(106, 'Fiona Chen', 'NON-IT', 88000, '2019-05-14'),
(107, 'George Smith', 'NON-IT', 71000, '2023-06-01'),
(108, 'Hannah Abbott', 'NON-IT', 75000, '2021-12-12'),
(109, 'Ian Mackaye', 'NON-IT', 64000, '2022-02-20'),
(110, 'Julia Santos', 'IT', 98000, '2023-08-19');

INSERT INTO Customers (name, country) VALUES 
('Liam Smith', 'USA'), ('Emma Brown', 'Canada'), ('Noah Garcia', 'Mexico'), 
('Olivia Jones', 'UK'), ('William Miller', 'Germany'), ('Sophia Davis', 'France'), 
('James Rodriguez', 'Spain'), ('Isabella Martinez', 'Italy'), ('Benjamin Hernandez', 'Brazil'), 
('Charlotte Lopez', 'Australia'), ('Lucas Gonzalez', 'Argentina'), ('Mia Wilson', 'Japan'), 
('Henry Anderson', 'South Korea'), ('Amelia Thomas', 'India'), ('Theodore Taylor', 'Netherlands'), 
('Evelyn Moore', 'Sweden'), ('Alexander Jackson', 'Norway'), ('Harper Martin', 'Denmark'), 
('Daniel Lee', 'Singapore'), ('Grace White', 'Ireland'),('Smith', 'USAUSA');
select * FROM Customers;

INSERT INTO orders (customer_id, order_date, total_amount) VALUES 
(1, '2023-11-01', 150.50), (2, '2023-11-02', 89.99), (3, '2023-11-03', 210.00),
(4, '2023-11-05', 45.00), (5, '2023-11-05', 320.75), (6, '2023-11-06', 12.50),
(7, '2023-11-08', 99.00), (8, '2023-11-10', 550.25), (9, '2023-11-12', 25.40),
(10, '2023-11-13', 135.00), (1, '2023-11-15', 75.20), (2, '2023-11-16', 110.00),
(3, '2023-11-18', 300.00), (11, '2023-11-19', 45.99), (12, '2023-11-20', 88.50),
(13, '2023-11-22', 1200.00), (14, '2023-11-23', 62.00), (15, '2023-11-25', 9.99),
(19, '2023-11-26', 215.00), (20, '2023-11-27', 54.30);
