# calculator
this is the small python code of calculator which may help to make your calculation easy.
def calculate(num1, num2, operator):
  if(operator == '+'):
    return num1 + num2
  if(operator == '-'):
    return num1 - num2
  if(operator == '*'):
    return num1 * num2
  if(operator == '/'):
    return num1 / num2
a=int(input("Input number1:"))
b=int(input("Input number2:"))
o=input("Input operator:")
c=calculate(a,b,o)
print(c)
