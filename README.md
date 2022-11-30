# Week1--Python--CipherSchools


# ACT1.py-CipherSchools

# **********print these followig lines **************
# this is \\ double backslash
# these are /\/\/\/\/\ mountains
# he is  awesome (use escape sequence instead of manual spaces)
# \ " \n \t\ '
print("**********print these following lines **************")
print("this is a \\\\ double backslash")
print("these are /\\/\\/\\/\\/\\ mountains")
print("he is\tawesome")
print("\\ \" \\n \\t\\ \'")


# ACT2.py-CipherSchools

# ask user to input three numbers and you have to print average of three numbers 
# using string formatting

num1, num2, num3 = input("Enter num1 num2 and num3: ").split()
avg = int(num1 +num2+num3)/3
print(avg)


# ACT3.py-CipherSchools

# Ask user name and print back user name in re erse order
name , = input("Enter your name: ")
print(name[ : :-1])
Footer
© 2022 GitHub, Inc.
Footer navigation


# ACT4.py-CipherSchools

# take two comma seperated input from user 
# output-2  print lines
# 1.) user name length
# 2.)count the character that user inputed
name, input = input("Enter the name and input word: ").split(",")
print(len(name))
print(name.lower().count(input.lower()))


# ACT5.py-CipherSchools

name=input("Enter your name:  ")
print(name.center(len(name)+8,"*"))


# ACT6.py-CipherSchools

wining_number = 3
guess_number= int(input("Enter any number here between 1 to 10: "))
if guess_number == wining_number:
    print("you win !!")
if guess_number> wining_number:
    print("too high")
if guess_number< wining_number:
    print("too low")
    
    
# ACT7.py-CipherSchools

# EXERCISE - watch COCO
# ask users name and age
# if users name start with(a or A) and age is above 10 then
# print you acn watch COCO
# else print sorry you can't watch coco movie
name = input("Enter your name: ")
age = input("Enter your age: ")
age = int(age)
if age >= 10 and (name[0]=="A" or name[0]=="a"):
    print("you can watch coco")
else:
    print("sorry! you can't watch coco")
    


# ACT8.py-CipharSchools

# sum of n natural numbes
# ask a user for natural number n
# print total from 1 to n
a = input("Enter a number here: ")
total = 0
i = 1
while i <= int(a):
    total = total + i
    i = i+1
print(total)


# ACT9.py-CipherSchools

# ask user to input a number containing more than one digit
# example-1256
# calculate 1+2+5+6 and print


a = str(input("Enter a four digit number here: "))
b = int(a[0])+int(a[1])+ int(a[2])+int(a[-1])
print(b)

# ACT10.py-CipherSchools

num=input("Enter number here: ")
total = 0
i = 0
while i< len(num):
    total = total +int(num[i])
    i = i+ 1
print(total)


# ACT11.py-CipherSchools

name = input("Enter your name: ")
temp_var = ""
i = 0
while i < len(name):
    if name[i] not in temp_var:

        temp_var+= name[i]
        print(f"{name[i]}: {name.count(name[i])}")
    i += 1
    

 
