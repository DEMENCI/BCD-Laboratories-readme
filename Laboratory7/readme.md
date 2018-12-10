## Databases Laboratory Work Nr.7


### Prerequisites:
  - Microsoft SQL Server 2012
  - Oracle 11g/12c

### Objectives:
  - T-SQL and Oracle data types and build-in functions
  - SQL Server Data Types and Functions
  - Query and Subquery
  - Agregate Functions
  - While, Try-Catch, If-Else
  - Creating tables and indexes
  - Diagrams, Schemas and Synonyms
  
 ### Tasks: 
 
 1. Create a database diagram , using the standard form of vizualization, structure which is described at the beginning practice items in
 4 chapter. 
 
 2. Add the references constraints ( for **studenti** and **profesori** tables) needed 'Sef_Grupa' , 'Prof_Indrumator' columns from **grupe** table. 
 
 3. At the performed diagram , should to add **orarul** table. Table **orarul** contains the 'disciplinei' identifier (Id_Disciplina) , profesor's identifier(Id_Profesor) and study block (Bloc). Table key is formed by fields: Id_Grupa, Zi, Ora, Auditoriu. 
 
 4. **Orarul** table should contains 2 secondary keys: (Zi, Ora, Id_Grupa, Id_Profesor), (Zi, Ora, Id_Grupa, Id_Disciplina). 
 
 5. In the diagram should be added the PK-FK for Id_Disciplina, Id_Profesor, Id_Grupa attributes from **orarul** table with those attributes from tables. 
 
 6. Create the new 3 schemas : cadre_didactice, plan_studii, studenti. Transfer profesori from dbo schema to 'cadre_didactice' schema , discipline to 'plan_studii', studenti and studenti_reusita to 'studenti'. Write the needed SQL instructions. 
 
 7. Modify the 2-3 queries from chapter 4 on the 'universitatea' database for explicitly addressing at the tables, taking into account that tables are in the new schemas. 
 
 8. Create synonyms for simplify the queries performed in the previous item and perform the queries , using the created synonyms. 
 
 ### Implementation:
 
 **Task 1** 
 
 ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_1.png) 
 
 **Task 2** 
 
 In this task we can manually do the refereces constraints. Just Select the field and keep pressed till the needed field from another table. 
 
 ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_2.png) 
 
 **Task 3** 
 
  ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_3.png) 
  
 **Task 4**
  
   ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_4.png)
   
**Task 5**  

Defining the PK-FK for tables, I have also chose the manually way , because is easier and take short time. 

 ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_5.png) 
 
**Task 6** 

 ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_6.png) 
 
 
 **Task 7** 
 
  ![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_7.png) 
  
  
 **Task 8** 
 
 Before performing this task I have read about synonyms what are their purpose for T-SQL instructions. These are vey useful for writing queries and don;t writing the explicitly location of tables. Also, they are very useful in cases of having more servers which are different located and we need access databases. 
 

![](https://github.com/DEMENCI/BCD-Laboratories-readme/blob/master/Laboratory7/Pictures/lab7_8.PNG)


**Conclusion:** 

During this laboratory work I have obtained others useful skills operating with Management SQL Studio, creating the diagrams, schemas and synonyms. I learned how write the queries using the explicit location of tables 'universitatea.studenti.studenti'.Schemas are the  way to separate database users from database object owners. In one schema we can include a lot of tables.

