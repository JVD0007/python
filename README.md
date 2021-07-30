Def Fibonacci(Num):
 If(Num == 0):
 Return 0
 Elif(Num == 1):
 Return 1
 Else:
 Return (Fibonacci(Num – 2)+ Fibonacci(Num – 1))
N= int(input(“\nPlease Enter the Range Number: “))
# Find & Displaying Fibonacci series
For I in range(0, N):
 Print(Fibonacci(i),end=’ ‘)
