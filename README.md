###............................... Chapter 4 (If / Else)......................................


##problem 3 :

for i in range(2) :
    temp = eval(input("enter a temperature in Celsius : "))  
    if temp < -273.15 :
        print("the temperature is invalid because it is below absolute zero")
    elif temp == 273.15 :
        print("the temperature is absolute 0")
    elif -273.215 < temp < 0 :
        print("that the temperature is below freezing")
    elif temp == 0: 
        print("the temperature is at the freezing point")
    elif 0 < temp < 100 :
        print("the temperature is in the normal rang")
    elif temp ==100 :
        print("the temperature is at the boiling point")
    elif temp > 100 :
        print("the temperature is above the boiling point")
        
print("The loop is ended")
        


## Problem 4 :

for i in range(2) :
    temp = eval(input("enter a temperature in Celsius : "))   
    if temp <= 23 :
        print("the student is a freshman")
    elif 24 <= temp <= 53 :
        print("they are a sophomore")
    elif 54 <= temp <= 83 :
        print("Junior")
    elif temp >= 84 :
        print("Senior")      
print("The loop is ended")




### Problem 5 : 

from random import randint
random_number = randint(1,10)
for i in range(5) :
    num = eval(input("Guess the number : "))
    if num == random_number :
        print("Right")       
    else :
        print("Wrong")      
    print("Random Number : ",random_number , "\n")
    
 
 
 
 ### problem 6 :
 
item = eval(input("How many items you buy : "))
if item < 10 :
    print("A store charges $12 per item")
    print("Total Cost : ", item*12)  
elif item in range(10, 100) :
    print("the cost is $10 per item")
    print("Total Cost : ", item*10)   
elif item >= 100 :
    print("the cost is $7 per item")
    print("Total Cost : ", item*7)

















