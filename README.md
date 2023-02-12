# local library database system

### problem statement
> A local library wants to keep track of the books they have in their collection.

> they want to be able to store the book `title`, `author`, and `publication year`, as well as keep track of which books are currently checked out to users

### solution 
> to solve this problem, a database can be designed to store infor,mation about the books in the library collection.

this database will have a table called `books` which will store the information about the each book:  

**Book** 
- `title`     : the title of book
- `author`    : the name of the author of the book 
- `publication year`    : the year  book was published
- `checked out` : a indicating value whether the book is currently checked out to user or not 

#### sample book collection

|    title     |   author  | publication year  |checked out  |
|   ---        |  ---     |     ---         |     ---     |
| the guide   |  r.k. narayan  |   1958      |   no     | 
|  train to us |    singh     |  1978       |   no    |
| white tiger  |  salman    |   2008   |   yes    |
| small things  |    roy    |   1995    |    yes   |
| java script handbook |    roy    |   2006   |   yes |

### librery system operations

1. **C**reate book
2. **R**ead  book
3. **U**pdate book
4. **D**elete book

CRUD - `Create read update delete
![]()
