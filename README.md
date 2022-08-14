print'''
+  Addition
-  Substraction
*  Multiply
/  Divide

num1=(int(input(Enter the Value1:-))
opr=input("Enter the operator(+,-,*,/):-")
num2=int(input("Enter the value2:-"))

if opr=="+":
    print(num1 + num2)
if opr=="-":
    print(num1 - num2)
if opr=="*":
    print(num1 * num2)
if opr=="/":
    print(num1 / num2)
if opr!="+" and opr!="-" and opr!="*" and opr!="/":
    print("invalid")
