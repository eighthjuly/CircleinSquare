# CircleinSquare
To make a circle using only square symbol
import turtle
my_turtle=turtle.Turtle()
my_turtle.speed(0)
def square(length,angle):#passing arguments 
    for j in range(4):
        my_turtle.forward(length)
        my_turtle.right(angle)
for i in range(72):# Basically i'm telling tp draw four times the square
    #square(50,90)#passing values
    square(100,90)
    my_turtle.right(5)   
    
#for perfect square we need to calculate how much degree we really need
#so circle is 360
#we used 5
#we should use 360/5=72
