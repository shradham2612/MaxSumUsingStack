# MaxSumUsingStack


###### In this assignment we have 3 stacks given and we have to find out maximum possible sum by popping out the elements of the stack

###### The idea is to compare the sum of each stack, if they are not same, remove the top element of the stack having the maximum sum.

<hr>

###### Algorithm for solving this problem: 

Find the sum of all elements of in individual stacks.
If the sum of all three stacks is the same, then this is the maximum sum.
Else remove the top element of the stack having the maximum sum among three of stacks. Repeat step 1 and step 2.

> We have used STL for ease of implementation



#### Output
> CASE_1:
###### enter the no of elements for stack 1 --5
###### 1 1 1 2 3
###### enter the no of elements for stack 2 --3
###### 2 3 4
###### enter the no of elements for stack 3 --4
###### 1 4 1 1
###### After popping :
###### 2 1 1 1 
###### 3 2 
###### 4 1 

###### Max Probable sum----5



> CASE_2:

###### enter the no of elements for stack 1 --3
###### 3 5 8
###### enter the no of elements for stack 2 --5
###### 2 2 4 9 6
###### enter the no of elements for stack 3 --4
###### 2 1 2 3
###### After popping :
###### 5 3 
###### 4 2 2 
###### 3 2 1 2 

###### Max Probable sum----8



>CSE 5A-22
