## （A3） Injection
### 1. SQL Injection (intro)
+ 1-2，查询语句  
```
select department from Employees where first_name='Bob'
```
+ 1-3,修改语句
```
update employees set department='Sales' where first_name='Tobi'
```
+ 1-4,修改表，添加字段
```
alter table employees add phone varchar(20)
```
+ 1-5,修改权限
```
grant select on grant_right to unauthorized_user
```
