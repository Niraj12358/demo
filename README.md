#demo 
this is my first git reposistory

<br>
authour niraj pandey
def calculator(num1, num2,op):
    result=0
    if(op=="+"):
        result=num1+num2
    elif (op=="-"):
        result= num1 -num2
    elif(op == "*"):
        result =num1*num2
    elif(op=="/"):
         result=num1/num2
    else:
         result =0;
    return result;
ch="y"
while ch =="y":

    number1 =int(input("enter a number :"))
    number2 =int(input("enter second numbaer : "))
    op=input("enter the operator :")
    finalResult =calculator(number1,number2,op);
    print(finalResult)
    ch= input ("Do you want to continue (y/n) : ")


