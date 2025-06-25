# Task2

Created a table,inserted a data and added a constraint for default values, updated and deleted data using where clause.

/*Create table task2 (
name varchar(15),
class varchar(8),
section char(2));

insert into task2 (name,class,section) values  
('Varun','BCA3','A'),
('Tapsya','BCA3','A'),
('Shamu','BCA3','A'),
('Vishal','BCom3','A'),
('Abhay','BCA3','A');

update task2 Set class='BCA3' where name = 'Vishal';*/

delete from task2 where name= 'Varun';
select * from task2;

