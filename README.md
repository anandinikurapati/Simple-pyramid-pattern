# Simple-pyramid-pattern
def pypart(n):
     
    # outer loop to handle number of rows
    # n in this case
    for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ",end="")
      
        # ending line after each row
        print("\r")
 # approach-2
 def pypart(n):
    if n==0:
        return
    else:
        pypart(n-1)
        print("* "*n)
  
# Driver Code
n = 5
pypart(n)
# approach-3
n = 5
for i in range(0, n):
    for j in range(0, i+1):
        print("*", end=" ")
    print()
