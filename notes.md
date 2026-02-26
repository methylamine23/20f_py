print("wwdwd")
#multiline string
print("""this 
 is a 
multiline 
string """)
#This is how you add strings togather 
print("this is string 1" + " this is string 2" + 
      " \nthis is string 3")
print("adam\t" * 3)#This is how you multiply

#Varriable in python
print("Hello, welcome to networchuck coffe!")

name = input("What is your name?") #takes input from user & when you place it inside print it prints back the user input
print("Hello, " + name)
menu = "Black coffe , Espresso, Latte, Cappucino"
print(name + """, what would you like from our menu 
today? Here is what we are serving.\n""" + menu)
#Python Maths
order = input()
price = 8
quantity = input("How many coffes?")
#total = price * quantity   if you type it like this then it'll be int(8) * string(quatity).. like printing something 8 times 1010101010101010
total = price * int(quantity) #converted string into and interger 
print("thank you, your total will be: $" + str(total)) #converted int into string
print("we'll have your\t" + order +" ready for you")

name = "Tawsir"
age = 31
actual_age = 21.7 #floating number
print(type(name))#type-to find out what type of data the varriable name is
print(type(age))
print(type(actual_age))


#conditional statement 
name = input("what is your name?\n")



#more of this 
#filter out the evil bens
name = input("what's your name?") #Nested loops 
if name == "Ben":
    evil_status = input("Are you evil?\n")
    if evil_status == "yes":
        print("you're not welcome here")
        exit()
    else:
        print("so youre one of those good bens, come on in")    
else:
   print("Hello " + name + "welcome")
#elif statements
 
if order == "Frapaccino":
  price = 13
elif order == "Black Coffe":#elif is kind of on equal footing with 'if'
  price = 3
elif order == "Cappucino":
  price = 10      
else:
   print("sorry, we dont have that here")   

#Logical operators 
name = input("what's your name?") #Nested loops 
if name == "Ben" or name == "patricia":
    evil_status = input("Are you evil?\n")
    if evil_status == "yes":
        print("you're not welcome here")
        exit()
    else:
        print("so youre one of those good bens, come on in")    
else:
   print("Hello " + name + "welcome")
#python lists
