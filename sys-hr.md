# employee active filter function 

```
select * from workplaze.employee_active_filter(current_date, '', 'ALL', 'ALL', 'ALL', null, 0)
```
1  Date <br>
2 name or nik <br>
3. company => ALL, PTCT,SCN,Vlr.intl <br>
4. Contract type => ALL, Employee, Outsourcing, Internship <br>
5. Contract Status => ALL, P,C,A <br>
6. Limit => Null for All data, get 10 <br>
7. Offset => 0 for start from 0 

# employee All

```
select * from workplaze.employee_all('', 'ALL', null, 0)
```
1. FIlter name , nik
2. Company => ALL, PTCT,SCN,Vlr.intl <br>
3. Limit => Null for All data, get 10 <br>
4. Offset => 0 for start from 0 
