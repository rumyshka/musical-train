# musical-train
import math 
print("ax^2+bx+c=0:") 
 
a=float(input("a=")) 
 
 
b=float(input("b=")) 
 
 
c=float(input("c=")) 
 
D=float(b**2-4*c*a) 
 
print("D=",D) 
if D<0: 
    print("no roots") 
if D>0: 
    x1=float((-b+math.sqrt(D))/(2*a)) 
    x2=float((-b-math.sqrt(D))/(2*a)) 
    print(x1,x2) 
if D==0: 
    x=float(-b/(2*a)) 
    print(x)
