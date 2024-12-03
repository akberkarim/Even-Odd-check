number = int(input("Enter any random number: "))

square = number * number 

if square % 2 == 0:  
    print(f"The square of the number is even.")
    square += 5  
else: 
    print(f"The square of the number is odd.")
    square -= 5  

print(f"The final result is {square}.")
