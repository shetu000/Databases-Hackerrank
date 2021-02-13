# Databases-Hackerrank

#After click on "RUN CODE" if you found this "No sample test-cases for this question. Please test your code against custom input." then don't panic simply just submit your code and it will show test case successfull
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

Q8: __Relational Algebra - 3__

```
Which is a join condition contains an equality operator?

```
###### Answer: Equijoins - joining against equality
###### FROM t1
###### JOIN t2
###### ON t1.id=t2.id






