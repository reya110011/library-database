### CREATE BOOKS TABLE

> BOOKS TABLE WILL HAVE FOUR COLUMNS
1. TITLE
   -TEXT
  1. Author
      - text 
1.publication year
        - date -> year 
1. checked
   - tinyint (1=yes and 0=no)  


   ```sql
   create table `library` . `books` (`title` text not null, `author` text not null, `publicationyar` year not null, `checked` tinyint not null )  engine = innodb;   
   ```

   ```sql
   create table  `library`. `books`
  (
    `title` text not null,  
    `author` text not null, 
  `publication year` year not null,
`checked` tinyint not null
)
   ```                              