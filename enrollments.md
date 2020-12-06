# Assignment 1 : enrollments
Write queries to answer the following questions based on enrollments database

## Getting Started
For this assigment, you will need `enrollments.csv` file. You can download it from [here](https://drive.google.com/drive/folders/1iL7DpsceRNsHEsxSHVHGqul5Of4Bznaf?usp=sharing).


## Understanding
A CSV file called  `enrollments.csv` is provided to you. It stores enrollments data at aiadventures (its a dummy dataset, randomly generated using a python script). 

In a terminal window, run `sqlite3` to start the SQLite. Then follow the steps below to load the data from CSV file.
- Set *mode* to *csv* by executing `.mode csv` inside sqlite3.
- Now you can import the data into *enrollments* table, by executing `.import enrollments.csv enrollments`.

## Questions
### Selecting Data
1. Select name, email, & course for all the records.
2. Select all the student names who enrolled for python after 2019.
3. Select all the records of students who enrolled for courses which have "learning" in their name.
4. Select all the students who completed the course in 5, 7 or 9 weeks.

### Operations
1. Select all the students who enrolled for python course. Sort them based on joininig data (latest at the top), and if there are multiple people who joined on the same date, then order them alphabetically based on their names. 
2. What is the average time required to complete the machine learning course?
3. List all the different courses that aiadventures offer.
4. What is the average, minimum & maximum time required for all the courses? Also, show the course names.

### CRUD
1. Try inserting a new record. Imagine you are joining a course at aiadventures. Keep the duration field empty.
2. Update the duration for the record that you entered in the last question.
3. Delete any record.

## Resources
- See [this SQL keywords reference](https://www.w3schools.com/sql/sql_ref_keywords.asp) for some SQL syntax that may be helpful!
- You can also refer [this quick guide](https://www.tutorialspoint.com/sqlite/sqlite_quick_guide.htm) for SQLite concepts & syntax. 



> Click for [Next assignment](movies.md)
