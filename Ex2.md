# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:


### OUTPUT:
![ex 2 01](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/32738588-a96e-4031-89b9-88376d8d873a)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:


### OUTPUT:
![ex 2 02](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/356d7a8b-589b-4dd8-a9f2-6b431100ddc5)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:


### OUTPUT:
![ex 2 03](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/8a03d1fd-9bb6-4ca6-8184-f7b7a76c65bd)


### Q5)	List the names of Clerks from emp table.


### QUERY:


### OUTPUT:
![ex 2 05](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/a82ed182-5834-41f0-95ea-b6fbe01cdc2b)


### Q6)	List the names of employee who are not Managers.


### QUERY:


### OUTPUT:


### Q7)	List the names of employees not eligible for commission.


### QUERY:


### OUTPUT:


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:


### OUTPUT:
![ex 2 08](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/4ec205d9-7a80-4dca-b4e5-c0f3ee1b3927)



### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:


### OUTPUT:
![ex -2 09](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/cbbafdb9-4294-4cfe-87f5-fee09da4824f)



### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:


### OUTPUT:
![ex 2 10](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/380a584b-3935-4c94-9325-b289afa2294f)



### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:


### OUTPUT:
![ex 2 11](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/c97a9d71-3c1f-4bce-8b1b-c158bc9db8dc)



### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:


### OUTPUT:
![ex 2 12](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/234268fa-233c-48a7-8ab5-eb118b0d53cf)


### Q13) Find number of rows in the table EMP

### QUERY:


### OUTPUT:
![ex 2 13](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/f52d5180-c670-4072-9d25-7b2f2c13c9f6)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:


### OUTPUT:
![ex 2 15](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/c7c44649-2fa7-4461-b008-a0e6c58cebdb)



### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:


### OUTPUT:
![ex 2 14](https://github.com/AJAYASWIN-M/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118679692/e69c720b-f655-4d0a-8249-911436d43a20)
