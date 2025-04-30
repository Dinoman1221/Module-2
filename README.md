# Iterative statements:binary number pattern of n rows and m columns

## Aim:
To write a Python program that prints a binary number pattern consisting of n rows and m columns using nested loops, where each element in the pattern is the digit 1.

## Algorithm:
1.Start

2.Input the number of rows n

3.Input the number of columns m

4.Repeat the following steps for each row from i = 0 to n - 1:

5.For each column from j = 0 to m - 1:

6.Print the digit 1 without moving to the next line

7.After printing all columns in the current row, move to the next line

8.End

## Program:
```
n=int(input())
m=int(input())
for i in range (0,n):
    for j in range (0,m):
        print("1",end="")
    print()
```
## Output:
![image](https://github.com/user-attachments/assets/cd9978c2-d6a8-4631-9dee-6f875d042072)

## Result:
Thus, the python program was executed successfully
