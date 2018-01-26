# ERD-and-SQL-code


## Scenario for ERD

A student registers for up to 8 modules and each module has many students on it. Record the student ID, their full name and address and also each module ID and title. Also, each module is related to a specific course, each course has a course ID and a title. Also, each course is related to a department. Finally, each department has a department ID, a name, and a head of the department.

### ERD diagram

![ERD diagram](https://github.com/LukeShead/ERD-and-SQL-code/blob/master/ERD.JPG)


## SQL code

SQL is mainly used as a database programming language and has many different features to it, these can be used to edit, delete or create databases and tables within a system, an example of this is:

INSERT INTO (Student) VALUES (01,BOB,Jones,141 Baldwins Lane) What this does is implement a new tablen with the name 'Bob Jones' who lives on 141 Baldwins Lane, UPDATE (Student) SET (Tom) WHERE (First Name) IS (Bob) This changes the first tables first name to 'Tom' instead of 'Bob' if it recognizes 'Bob' in the table. DELETE FROM Student WHERE (First Name) IS (Tom) This deletes the record with the first name of 'Tom' and therefore the 'Bob' table
