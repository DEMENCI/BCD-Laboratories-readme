## Databases Laboratory Work Nr.4


### Prerequisites:
  - Microsoft SQL Server 2012
  - Oracle 11g/12c

### Objectives:
  - T-SQL and Oracle data types and build-in functions
  - Constraints
  - Creation, rename and update table
  - SQL Server Data Types and Functions
  - Query and Subquery
  - Agregate Functions
  
  
### Tasks : 

1.Find out all the data about groups from faculty  

2.Show the list of disciplines in descending order of number of hours  

16.Provide the name and surname of the students who have studied lessons less than 60 hours,
as well as the identities of the teachers who taught them.

21.How many grades have each of students. Show the name and surname 

22.Show the number of disciplines that are taught by each professor. (Nume_Profesor, Prenume_Profesor) 

24.Display the list of disciplines(Disciplina) that is taught at least 2 professors. 

### Implementation:
**Task 1**  

![](https://github.com/gzaharia/BDC_Labs/blob/master/Laboratory_Work_N4/Screens/Ex1.PNG) 

**Task 2** 

![](https://github.com/gzaharia/BDC_Labs/blob/master/Laboratory_Work_N4/Screens/Ex2.PNG) 

**Task 16**

![](https://github.com/gzaharia/BDC_Labs/blob/master/Laboratory_Work_N4/Screens/Ex16.PNG) 

**Task 21**

Here , I have applied another feature of SQL that is called subquery and more precious in *FROM* clause. First , I performed an *select*
in the FROM clause for getting the  Id_Student and NrOfGrades for each of them that was grouped by Id_Student and storing these values in table1 , which is an alias. For counting the NrOfGrades I have used the agregate function count().
Having the Id_Student and NrOfGrades from *studenti_reusita* we should perform the join with *studenti* for displaying the Name, Surname. 

![](https://github.com/gzaharia/BDC_Labs/blob/master/Laboratory_Work_N4/Screens/Ex21.PNG) 


### Conclusion: 
   In this laboratory work I obtained skills operatig with queries(T-SQL language).There are numerous ways of selecting data 
   from database. Even if the tables do not provide the neccesary information we can obtain through different combinations aka 
   joins between tables. There are also functions which can be perfomed on data e.g. counting, average etc.
