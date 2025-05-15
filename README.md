# conditional statements 
    num = 99
    if (num>0):
        print ("hi students")
    print ("india")
# another one
    num = -99
    if (num>0):
        print ("hi students")
    print ("india")
#conditional statement-3
    person =int(input("enter the age:"))
    limit = 18
    if person>=limit:
        print("eligible")
#conditional statement-4
    person =int(input("enter the age:"))
    limit = 18
    if person>=limit:
        print("eligible")
'''print whether the number is even and skip the condition is not'''
    num = int (*input("enter the number:"))
    if num%2==0:
        print("it is an even  num")
        print("manasa")
'''program to deter mined  the char entered  by a user ,whwether it is an alphabt,digit or space by using seperate if conditional and pre defined string functions'''
    char=input("press any key ")
    if char.isalpha():
        print("the user has entered character ")
    if char.isdigit():
        print("the user has entered digit")
    if char.isspace():
        print("the user has entered space")
'''write a program to find the thje smallest of two numbers by using if -else condition
where take a manual input from the user
a=-4
b=-99'''
    a=int(input("enter the value of a:"))
    b=int(input("enter the value of b:"))
    if a<=b:
        small = a
    else:
        small= b
        print("small value is ",small)
'''write a progra,m to enter the character (a to z),if the entere character is in lower converter to uppr converter viceversa
input =a
input = b
out put =b '''

    ch = (input ("enter the ch"))
    if ch >= 'A' and ch<='Z':
        ch= ch.lower()
        print("converted case of input ch :",ch)
    else:
        ch= ch.upper()
        print("convered case of input ch :",ch)
'''CHECK WHWETHE  THE GIVEN INPUT IS A LEAP YEAR FOR 4 YEAR AND CENTURIANS BY IF ELSE'''  
    y=int(input("enter the number:"))
    if y%4==0 or y%100==0 or y%400==0:
            print(y,"is a leap year")
    else:
            print(y,"is not a leap year")
'''write a program to check whether the given number is a positive ,negative  or zero '''
    num =int(input ("enter the number:"))
    if num==0:
        print("zero entered")
    elif num>0:
        print("positive")
    else:
        print("negative")
    
