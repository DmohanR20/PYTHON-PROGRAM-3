# PYTHON-PROGRAM-3
a program to find armstrong number
n=int(input("enter a number"))
temp=n
s=0
while temp!=0:
    r=temp%10
    s+=r*r*r
    temp=temp//10
if n==s:
    print("given number is armstrong")
else:
    print("given number is not armstrong")
print(s)
