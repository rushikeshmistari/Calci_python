#My CALCULATOR:-
#PLEASE USE PYTHON COMPILER
def sum(a,b):
    print("summation of",a,"and",b,"is",a+b)
def sub(a,b):
    print("subtraction of",a,"and",b,"is",a-b)
def mul(a,b):
    print("multiplication of",a,"and",b,"is",a*b)
def div(a,b):
    print("division of",a,"and",b,"is",a/b)
def mod(a,b):
    print("modulus of",a,"and",b,"is",a%b)
    
print("<----------‐----Simple Calculator---------------->")
print("Select :-\n1.summation\n2.substraction\n3.multiplication\n4.division\n5.modulus ")
print("<------------------Now Begin------------------>")
while (True):
        x=int(input("enter your choice :-"))
        if (x==1):
              z=int(input("enter first value:-"))
              y=int(input("enter second value:-"))
              sum(z,y)
        elif (x==2):
              z=int(input("enter first value:-"))
              y=int(input("enter second value:-"))
              sub(z,y)
        elif (x==3):
              z=int(input("enter first value:-"))
              y=int(input("enter second value:-"))
              mul(z,y)
        elif (x==4):
              z=int(input("enter first value:-"))
              y=int(input("enter second value:-"))
              if (y==0):
                  print("denominator cannot be zero")
              else:
                  div(z,y)
        elif (x==5):
              z=int(input("enter first value:-"))
              y=int(input("enter second value:-"))
              if (y==0):
                  print("denominator cannot be zero")
              else:
                  mod(z,y)
        else :
              break
        print("---------------------------------------------------")
print("Give Your Feedback")        
