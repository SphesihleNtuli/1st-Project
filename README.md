# 1st-Project/python/
Calculator(easy)
print("Welcome to my boring calculator")
Num1 = float(input("Enter number: "))  

Operation = input("Choose operation, make sure to use the following: + * - /: ")  

Num2 = float(input("Enter 2nd number: "))  

print("Your answer is:")

if Operation == "+":  
    print(Num1 + Num2)  

elif Operation == "-":  
    print(Num1 - Num2)  

elif Operation == "*": 
    print(Num1 * Num2)  

elif Operation == "/":  
    print(Num1 / Num2)
