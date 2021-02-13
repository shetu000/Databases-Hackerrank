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





