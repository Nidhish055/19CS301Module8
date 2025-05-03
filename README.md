# 19CS301Module8
EXPTNO.8a Program to Find Total Marks and Percentage

### Aim:

To Write a python program to read the marks of three subjects from the users and calculate the total and percentage for that particular student.

### Algorithm:

1. Start the program.  
2. Define variables `a`, `b`, and `c` to store marks for three subjects.  
3. Get the input marks for each subject from the user.  
4. Calculate the total marks as `total = a + b + c`.  
5. Calculate the percentage as `percentage = (total / 300) * 100`.  
6. Print the total marks and percentage.  
7. Stop the program.


### Program:

```python
# Reg no: 212223050032
# Name: Nidhish B

a=int(input())
b=int(input())
c=int(input())
print(f"Total marks obtained is {a+b+c} and the percentage obtained is {(a+b+c)/3}")

```

### Output:

![image](https://github.com/user-attachments/assets/af7a08b3-905c-4a40-8371-035bc289fea0)

### Result: 

Thus,the given program is implemented and executed successfully.


EXPTNo.8b Program to display elements from a list, present at odd index positions

### Aim: 

Write a python program to display elements from a list, present at odd index positions

### Algorithm:

1. Start the program.
2. Create an empty list `arr`.
3. Get the integer `n` (the number of elements) from the user.
4. Use a loop to input `n` integers and insert them into the list `arr`.
5. Use another loop to iterate over the indices of `arr`.
6. For each index, if it is odd (i.e., `i % 2 != 0`), print the element at that index.
7. Stop the program.


### Program:
```python

# Reg no: 212223050032
# Name: Nidhish B

arr = []
n=int(input())
for i in range(n):
  arr.insert(i, int(input()))


for i in range(n):
  if i%2!=0:
    print(arr[i],end=" ")
```
### Output:

![image](https://github.com/user-attachments/assets/2147a1bd-e0f0-469f-99a8-382ee75cfd9a)

### Result:

Thus, the given program is implemented and executed successfully.
 

EXPT NO>8C To write a program to store the details of students and grades in a nested list and print the name(s) of any student(s) having the second lowest grade.

### Aim:

To write a program to store the details of students and grades in a nested list and print the name(s) of any student(s) having the second lowest grade.

### Algorithm:

1. Start the program.
2. Create two empty lists `l1` and `l2` to store student names and grades.
3. Get the number of students `n` as input from the user.
4. Loop `n` times to get the name and grade for each student and append them to `l1`, then add `l1` to `l2`. After each loop, reset `l1` to an empty list.
5. Create an empty list `l3` to store grades from `l2`.
6. Sort the list `l3` containing the grades in ascending order.
7. Identify the second lowest grade by accessing the second element of `l3`.
8. Create an empty list `l4` and append the names of students whose grade matches the second lowest grade.
9. Sort the list `l4` alphabetically.
10. Print the names of the students with the second lowest grade.
11. Stop the program.


### Program:

```python

# Reg no: 212223050032
# Name: Nidhish B

l1=[]
l2=[]
for i in range(int(input())):
    name=input()
    mark=float(input())
    l1.extend([name,mark])
    l2.append(l1)
    l1=[]
l3=[]
l4=[]
for i in l2:
    l3.append(i[1])
l3.sort()
    
for i in l2:
    if i[1]==l3[1]:
        l4.append(i[0])
l4.sort()

for i in l4:
    print(i)

```  

### Output:

![image](https://github.com/user-attachments/assets/b15b7d66-b0fb-42b9-b8d2-9894d4e8299a)

### Result:

Thus, the given program is implemented and executed successfully.
 


EX: 8.d Program to square all the even numbers and cube all odd numbers from a list of integers

### Aim:

To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

1. Start the program.
2. Define the function `fun(f, l)` that returns a range of numbers from `f` to `l` (inclusive).
3. Define the function `cube(i)`:
   - If `i` is even, return `i**2`.
   - If `i` is odd, return `i**3`.
4. Get the input values for `f` and `l` from the user.
5. Call the `fun(f, l)` function to get the range of numbers from `f` to `l`.
6. For each number `i` in the range, call the `cube(i)` function and print the result.
7. Stop the program.

### Program:

```python
# Reg no: 212223050032
# Name: Nidhish B

def fun(f,l):
    return range(f,l+1)
    
def cube(i):
    if i%2==0:
        return i**2
        
    else:
        return i**3
        
f=int(input())
l=int(input())

```
### Output:

![image](https://github.com/user-attachments/assets/d95b6ae8-8e1c-4733-bda3-897113508961)


### Result: 

Thus,the given program is implemented and executed successfully.
 


