# SCAMP-Assessment
My solution to the Python assessment for She Codes Africa

def Fibon(n):
             if n<=1:
                 return n
             else:
                 return(Fibon(n-1) + Fibon(n-2))
nterms = int(input("Please enter the number of terms here: "))
if nterms <= 0:
    print("Enter a positive number: ")
else:
    print("Fibonacci sequence is: ")
    for i in range(nterms):
         print(Fibon(i)," ", end=" ")

