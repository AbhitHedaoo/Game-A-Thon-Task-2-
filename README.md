# Game-A-Thon-Task-2
## Name - Abhit Vijay Hedaoo
### Problem Statement - 1 : Python program to add two numbers.
TestCases: input: a,b

output: a+b

My approach: Taking two numbers and adding them.

a = int(input("enter first number: "))
b = int(input("enter second number: "))
 
sum = a + b
 
print("sum:", sum)

### Problem Statement - 2 : Python program to compute the sum of two matrices and then print it.

TestCases: input: X= [[1,2,3],
    [4 ,5,6],
    [7 ,8,9]]
 
Y = [[9,8,7],
    [6,5,4],
    [3,2,1]]
    
output: result= [[10,10,10],
         [10,10,10],
         [10,10,10]]
         
My approach: In this program we have used nested for loops to iterate through each row and each column. At each point we add the corresponding elements in the two matrices and store it in the result.

for i in range(len(X)):  

for j in range(len(X[0])):
        result[i][j] = X[i][j] + Y[i][j]
 
for r in result:
    print(r)
