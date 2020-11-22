### Query to Create table ###
create table student(roll_no int, first_name varchar(255), last_name varchar(255), course varchar(255));

### Add tuples (values) in table ###
insert into student(roll_no,first_name,last_name,course)
values('101','Kannu','Priya','Btech'),('102','Anamika','Verma','Bsc'),('103','Ashish','Pal','diploma'),('104','Shubh','Singh','Btech');

### Display Table ###
select *
from student;

### OUTPUT (Write display table query) ###
101|Kannu|Priya|Btech
102|Anamika|Verma|Bsc
103|Ashish|Pal|diploma
104|Shubh|Singh|Btech

### Add new column ###
alter table student
add phone_no varchar(15);

### insert new row with new column
values('105','Ram','Hari','Bcom','1234567895');

### OUTPUT (Write display table query) ###
101|Kannu|Priya|Btech|Null
102|Anamika|Verma|Bsc|Null
103|Ashish|Pal|diploma|Null
104|Shubh|Singh|Btech|Null
105|Ram|Hari|Bcom|1234567895

### insert values in already existing column ###
update student
set phone_no = '2345679664'
where first_name = '101';

### OUTPUT (Write display table query) ###
101|Kannu|Priya|Btech|2345679664
102|Anamika|Verma|Bsc|Null
103|Ashish|Pal|diploma|Null
104|Shubh|Singh|Btech|Null
105|Ram|Hari|Bcom|1234567895


### Modify existing data ###
Update student 
set couse = 'Mba'
where roll_no = '105';

### OUTPUT (Write display table query) ###
101|Kannu|Priya|Btech|2345679664
102|Anamika|Verma|Bsc|Null
103|Ashish|Pal|diploma|Null
104|Shubh|Singh|Btech|Null
105|Ram|Hari|Mba|1234567895

### Delete a row ###
delete from student
where roll_no = 105;

### OUTPUT (Write display table query) ###
101|Kannu|Priya|Btech|2345679664
102|Anamika|Verma|Bsc|Null
103|Ashish|Pal|diploma|Null
104|Shubh|Singh|Btech|Null

### delete table ###
drop table student;

### OUTPUT (Write display table query) ###
no such table: student







