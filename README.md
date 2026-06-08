# Simple-Converter-and-Calculator
This is a simple converter which uses, user's input and operation choosed and gives out the converted value, same goes with the calculatorprint("                                                                   Convertor and calculator                                                                           ")
print("                                                                           Menu                                                                                      ")



choice = int(input(("Choose 1 for Converter and Choose 2 for Calculator  : ")))
if choice == 1:
    print("Converter")

    Value = int(input("Enter the value : "))

    print("op1 = USD to INR")
    print("op2 = Km to m")
    print("op3 = L to ml")
    print("op4 = GB to MB")
    
    choose_operation = input("Choose op1, op2, op3, op4 : ")
    if choose_operation == "op1":
        print("The value is>>>" , Value * 95.40 , "INR")
    elif choose_operation == "op2":
        print("The Value is>>> ", Value * 1000, "m")
    elif choose_operation == "op3":
        print("The value is>>>", Value * 1000, "ml")
    elif choose_operation == "op4":
        print("The value is>>>", Value * 1024, "MB")
    else:
        print("Invalid option")
        

if choice == 2:
    print("Calculator")
    print("Operations = +, -, *, /")

    num1 = float(input("Enter the first number : ")) 
    op = input("Enter the op : ")
    num2 = float(input("Enter the second number : "))

    if op == "+":
        print("=", num1+num2)
    elif op == "-":
            print("=", num1-num2)
    elif op == "*":
        print("=",num1*num2)
    elif op == "/":
        print("=",num1/num2)
    
    else:
        print("Invalid option")

print("Thank you for using....")




