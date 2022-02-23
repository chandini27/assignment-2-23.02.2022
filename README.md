# assignment-2-23.02.2022
Write a program to print append 
a=[]
n=int(input('Enter n:'))
for i in  range(n):
    d=int(input())
    a.append(d)
print('mylist before reverse:',a)
a2=a
a2.reverse()
print('mylist after reverse',a2)
Output
Enter number:4
23
25
36
56
Mylist before reverse:[23,25,36,56]
Mylist after reverse:[56,36,25,23]
