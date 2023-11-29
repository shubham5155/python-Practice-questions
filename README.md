# #Swap the number without using third variable
x=int(input("enter the first number"))
y=int(input("enter the second number"))

print(x,y) 1

x=x+y
y=x-y
x=x-y

print(x,y)
# Write a program to extracr each digit from an integer in the reverse order.
a=345
x=a%10
a//=10
y=a%10
a//=10
z=a%10
a//=10
print(x,y,z)

#write a program that will give you the sum of three digits
a=678
x=a%10
a//=10
y=a%10
a//=10
z=a%10
a//=10
print(x+y+z)

#write a program that will reverse a four digit number.Also it checks whether the reverse 
a=1221
b=1221
x=a%10
a//=10
y=a%10
a//=10
z=a%10
a//=10
c=a%10
a//=10
s=x*1000+y*100+z*10+c
if s==b:
    print("s is equal to b")
else:
    print("s is not equal to b")

# write a program to find the eucledion distance between two coordinates.
import math
x1=float(input("x1"))
y1=float(input("y1"))
x2=float(input("x2"))
y2=float(input("y2"))

x=[x1,y1]
y=[x2,y2]

print("="*100)

print("Eucledian distance for given co-ordinate will be",round(math.dist(x,y),2))

#Write a program that will tell whether the given number is divisible by  3 & 6.
a=int(input("enter he number"))
if a%6==0:
    print("Number is divisible")
else:
    print("Number is not divisible")

#write a program that will take three digits from the user and add the square of each digit.
a=int(input("Enter the three digit number"))
x=(a%10)**2
a//=10
y=(a%10)**2
a//=10
z=(a%10)**2
a//=10
print(x+y+z)

# #Write a program that will check that the number is amstrong or not.
a=int(input("Enter the three digit number"))
b=a
x=(a%10)**3
a//=10
y=(a%10)**3
a//=10
z=(a%10)**3
a//=10
i=(x+y+z)
if b==i:
    print("The number is armstrong")
else:
    print("The number is not armstrong")

#Accept number fromn the user
name=int(input("enter the Number:"))

# Display the string "Name","is","james" as "Name**is** james".
print("name","is","James",sep="**")

# convert decimal number to octal using print() output formatting.
a=int(input("Enter the decimal number"))
print("octal number is",oct(a))














