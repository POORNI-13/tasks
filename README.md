TASK 1

from math import pi
r = float(input ("Input the radius of the circle : "))
print ("The area of the circle with radius " + str(r) + " is: " + str(pi * r**2))

OUTPUT:

Input the radius of the circle : 1.1                                                                          
The area of the circle with radius 1.1 is: 3.8013271108436504 

TASK 2


filename=input("input the filename:")
f_extns=filename.split(".")
print("the extension of the file is :"+repr(f_extns[-1]))

OUTPUT:
input the filename:abc.py
the extension of the file is:'py'
