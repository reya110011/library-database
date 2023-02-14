### select statement

**select** rows from the table


### syntax
```sql
select 
   column_one,
   column_two, 
   ...
   from
      table_name
      ``` 

      ### example
      ```sql
      select
       title,
       author
      from
        books;
      ```
### select  all columns from the table
```sql
select * from books;
```


### select with where clause
```sql
select * from table_name where column=value
```

### where clause example
```sql
select
 title
  from
   books
    where
     checked=1
     ```