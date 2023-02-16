# Collage_Events

## 1. Create a table with column defination
-----
```Sql
create table Collage_event  (

event_Date Date,
event_Name varchar(100),
event_location varchar(150),
Students_list int,
budget flort,
note text,
)

```
#### 2. **c**reate a event record in table

```sql
insert into Collage_event (
event_Date,
event_Name,
event_location ,
Students_list,
budget,
notes,
) values (
    "20.03.2023",
    "freshers_day",
    "sv_university",
    "1000",
    "70000",
    "speaching"
);
```
#### 3. **R**ead events record from the table 
```sql
 select * from collage_event
 select * from collage_event WHERE event_Name="freshers_day"
```
#### 4. **U**pdate event record

```sql
UPDATE collage_event,
SET
   Studebts_list=1700,
   budget=60000
   WHERE
     event_name="freshers_day"
```
#### 5. **D**elete completed event

```sql
DELETE FROM collage_event WHERE event_name="freshers_day"
```



