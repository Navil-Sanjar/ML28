# ML28
Python Assigmnent1

Python code for Assignment Question no.1
In [ ]:
#PROGRAM TO FIND NUMBERS IN BETWEEN RANGE OF 2000 AND 3200 ( BOTH INCLUSIVE) WHICH ARE DIVISIBLE BY 7 AND NOT MULTIPLES OF 5.OUTPUTS ARE SEPARATED BY COMMA 
#type(x)==int:
#type(y)==float:
for x in range(2000,3200):
     if (x%7==0):
        y=(x/5.0)
        if(y%5!=0):
            print(str(x)+',')
Python code for Assignment Question no.2
In [ ]:
# A Python program to accept the user's first and last name and then getting them printed in the the reverse order with a space between first name and last name
first_name=input('Enter your 1st name')
last_name=input('Enter your last name')
s=first_name[::-1]+' '+last_name[::-1]
print(s)
Python code for Assignment Question no.3
In [ ]:
#A Python program to find the volume of a sphere with diameter 12 cm.

pi=3.14 #taking approx value of pi
r=6.0 #since d=r/2
v=4/3*pi*r**3
print('the volume of a sphere with diameter 12 cm. is ',v)
In [ ]:
