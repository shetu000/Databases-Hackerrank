# Databases-Hackerrank

*__NOTE:__* After click on "RUN CODE" if you found this *__"No sample test-cases for this question. Please test your code against custom input."__*then don't panic simply just submit your code and it will show test case successfull
###### (do not write the ans description only write the exact ans and directly submit because there is not extra test cases for the quaries)



Q1.*__Basics of Sets and Relations #1__*
```You are given two sets
Set A = {1,2,3,4,5,6}
Set B = {2,3,4,5,6,7,8}
How many elements are present in  A U B?
Only enter the correct integer in the editor below. Do not include any extra spaces, tabs or newlines.
```


###### ANS: 8 (description: A U B={1,2,3,4,5,6,7,8})


Q2: *__Basics of Sets and Relations #2__*
```Set A = {1,2,3,4,5,6}
Set B = {2,3,4,5,6,7,8}
How many elements are present in ?
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
```
###### ANS; 5

Q3: *__Basics of Sets and Relations #3__*

```
You are given two sets.
Set A = {1,2,3,4,5,6}
Set B = {2,3,4,5,6,7,8}
How many elements are present in A - B?
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
```
###### ANS: 1
###### A - B = {1,2,3,4,5,6} - {2,3,4,5,6,7,8} = {1}


Q4: *__Basics of Sets and Relations #4__*
```
You are given two sets.
Set A = {1,2,3,4,5,6}
Set B = {2,3,4,5,6,7,8}
What is the total number of ordered pairs present in the Cartesian Product AXB  ? Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.
```
###### ANS:42
###### set A = 6 values
###### set B = 7 values
###### so number pairs in cartesian product (AXB) = 6*7 =42

Q5: *__Basics of Sets and Relations #5__*
```
Consider the following data table named Student.
Student Name    Number  Sex  
Ben             3412    M  
Dan             1234    M  
Nel             2341    F  
What is the count of rows returned in the following relational selection?
σ(Number<3000)(Student)
Only enter a single integer. Do not include any extra spaces or newlines.
```
###### ANS:2
###### Because Number 3412 < 3000 and Number 2341 < 3000 (only 2 records)

Q6: *__Basics of Sets and Relations #6__*

```
Consider the following data table named Student.

Name                Number  Sex  
Nina                3412    F 
Mike                1234    M  
Nelson              2341    F  
What is the count of attributes (columns) returned in the following projection?
π(Name, Number)(Student)

Only enter a single integer. Do not include any extra spaces or newlines.
```
###### ANS:2
###### Because there is only two column "Name" and "Number"

Q7: __Basics of Sets and Relations #7__

```
Consider the following data table named Student.

Student Name        Number  Sex  
Nina                3412    F 
Mike                1234    M  
Nelson              2341    F  
Here is another data table named Teaching Assistants

Subject     ID
Physics     3412
Chemistry   1111
Mathematics 2341  
What is the count of rows returned in the following join operation?
Student ⊳⊲(Number=ID) Teaching Assistants

Only enter a single integer. Do not include any extra spaces or newlines.
```
###### ANS:2
###### Because In Student table and Teaching Assistants tahble 2 records are similar they are Number=ID=3412 and Number=ID=2341

Q: *__Relational Algebra - 3__*

```
Which is a join condition contains an equality operator?

```
###### Ans: Equijoins

Q: *__Relational Algebra - 4__*
```
In precedence of set operators the expression is evaluated from:
```
###### Ans:Left to right

Q: *__Database Query lANGUAGE__*
```
Using which language can a user request information from a database ?
```
###### Ans:Query

Q: *__Procedural language__*
```
Which one of the following is a procedural language ?
```
###### Ans:Relational algebra

Q: *__Relations-1__*
```
The_____ operation allows the combining of two relations by merging pairs of tuples, one from each relation, into a single tuple.
```
###### Ans:Join

Q: *__Relations-2__*
```
The result which operation contains all pairs of tuples from the two relations, regardless of whether their attribute values match.
```
###### Ans:Cartesian product

Q: *__Index Architecture Types__*
```
How many index architecture type classifications are there in MS SQL Server?
```
###### Ans:2

Q: *__Indexes-2__*
```
Which of the following statement is true about row locators in non-clustered indexes in MS SQL Server?
```

###### Ans:If the table has a clustered index, or the index is on an indexed view, the row locator is the clustered index key for the row.

Q: *__Indexes-3__*
```
Consider the following two designs to store the data using clustered indexes in MS SQL Server:
In the first design, the fill factor is 20% and the total number of free rows per page are A.

In the second design, the fill factor is 40% and the total number of free rows per page are B.

Which the followings describes the relation between A and B:
```

###### Ans:A = 1.33B

Q. *__Indexes - 4__*
```
The correct syntax for creating composite indexes in MS SQL Sever is:
```
###### Ans:<p>CREATE INDEX index_name</p> <p>ON table_name(column1, column2);</p>

Q. *__OLAP Performance__*
```
Which of these helps OLAP speed up queries, in terms of performance?
```
###### Ans:Aggregation

Q.__*OLAP Operations - 1__*

```
This OLAP operation involves computing all of the data relationships for one or more dimensions.
```
###### Ans:roll-up

Q.__*OLAP Operations - 2__*
```
This OLAP Operation rotates the data, and delivers an alternative to the original presentation.
```
###### Ans:pivot

Q. *__OLAP Cube Metadata__*

```
What is the source of the cube metadata for OLAP?
```
###### Ans:Both star and snowflake schema(s)

Q.*__OLAP Name(s)__*

```
Which of these are alternate names for an OLAP Cube? The options in the top row are a and b respecitvely and those in the bottom row are c and d.
```
###### Ans: Both (B) and (C) (Multidimensional Cube+Hyper Cube)


Q.*__The Total View__*

```
Which of these provides a total view of the organization?
```
###### Ans: Data Warehousing

Q.*__OLAP Operation Types__*

```
Consider a fact table DataPoints(D1,D2,D3,x), and the following three queries:

Q1: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3

Q2: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3 WITH CUBE

Q3: Select D1,D2,D3,Sum(x) From DataPoints Group By D1,D2,D3 WITH ROLLUP
Suppose attributes D1, D2, and D3 have n1, n2, and n3 different values respectively, and assume that each possible combination of values appears at least once in the table DataPoints. The number of tuples in the result of each of the three queries above can be specified as an arithmetic formula involving n1, n2, and n3. Pick the one tuple (a,b,c,d,e,f) in the list below such that when n1=a, n2=b, and n3=c, then the result sizes of queries Q1, Q2, and Q3 are d, e, and f respectively.
```
###### Ans:(4, 7, 3, 84, 160, 117)


Q.*__Database Normalization #1 - 1NF__*

```
The following unnormalized table named PRODUCT is transformed to first normal form (1NF) by splitting it into two tables which have X and Y rows (such that X <Y) respectively. Both the tables have Z columns.

*Product-ID*    *Colors*    *Price*
1               Red,Green   15.0
2               Blue        18.0
3               Yellow,Pink 2.5
What are the values of X, Y, Z? Enter these integers, each on a new line, in the text-box below. Do not leave any leading or trailing spaces.
```
###### Ans:3 
######     5
######     2

###### Because
###### 3 (1, 15.0), (2, 18.0), (3, 2.5)
###### 5 (Red, 15.0), (Green, 15.0), (Blue, 18.0), (Yellow, 2.5), (Pink, 2.5)
###### 2 *Product-ID* and *Price*, *Colors* and *Price*

Q.*__Database Normalization #2 - 1/2/3 NF__*

```
A particular database is normalized to satisfy a particular level of normalization (either 1NF or 2NF or 3NF). One of the tables contains, among other fields, a column for the City and a column for the Zip Code. Assuming that there is a many-to-one mapping between the set of Zip Code(s) and City, we may conclude that the database is definitely NOT in  x NF form. What is the integer x (1, 2, or 3)? Fill your answer in the text box below.
```
###### ANS: NOT IN 3NF

Q.*__Database Normalization #3__*
```
A database used by a college’s application stores the relationship between students and the courses they are enrolled in. We have information for each STUDENT (such as name, date of birth, date of enrollment, student-id) and COURSE (course code, instructor, etc.). In real life, a student takes several courses simultaneously while a subject is studied by several students. We need to capture this many-to-many relationship in our database. From the above information, what is the minimum number of tables required to structure this database in accordance with the rules of 2NF normalization?
```
###### ANS: 3

Q.*__Database Normalization #4__*

```
A database, normalized as per 2NF rules, has been split into 10 tables. Each of the tables has exactly two columns: one key attribute and one non-key attribute. What is the minimum number of tables required to express this database in 3NF form? Enter the integer in the text box below. Do not leave any leading or trailing spaces.
```
###### ANS:10
Q.*__Database Normalization #5__*
```
Consider the following relation and determinants.

R(a, b,c,d)

                   a,c -> b,d
                   a,d -> b
        Also, a,b is a primary key for the above relation.
The above relation is in x NF form where x may take the following values {1,2,3,3.5} corresponding to {1NF, 2NF, 3NF and BCNF} respectively.
What is the maximum possible value of x such that the above relation satisfies the *x*NF form?
Your answer should only be restricted to one of these numbers:1/2/3/3.5 Do not leave any leading or trailing spaces.
```
###### ANS:3

Q.*__Database Normalization #9__*
```
Consider the following relation and determinants. The key(s) are bolded.
R(a, b ,c,d,e)

Which of these determinants is a NON-CANDIDATE key? In the text box, only enter the index number (1-3) of the dependency which you have identified as non-key.

a,c -> b,d,e
a,d -> b
a,c,e -> b,d
```
###### ANS:2


Q.*__Database Normalization #10__*
```
The following table stores rows of information about pizza deliveries. The three columns correspond to the Restaurant name, Crust, Delivery Area. We convert this table into Fourth Normal Form and so we end up creating two tables, each with two columns and N rows. (Both the new tables have an equal number of rows)

Restaurant  Crust       Delivery Area
-------------------------------------------
X Pizza     Thick       Whitefield
X Pizza     Thick       Greenville
X Pizza     Thick       Capital
X Pizza     Stuffed     Whitefield
X Pizza     Stuffed     Greenville
X Pizza     Stuffed     Capital
Papa Pizza  Thin        Capital
Papa Pizza  Stuffed     Capital
F1 Pizza    Thick       Whitefield
F1 Pizza    Thick       Greenville
F1 Pizza    Thin        Whitefield
F1 Pizza    Thin        Greenville
In the text box below, enter the value of the integer N.
```

###### ANS:6



