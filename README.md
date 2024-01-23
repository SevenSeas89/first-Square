# first-Square
learning square vice triangle
import turtle
turtle.color("green")

# size = 120
# 4 Repeat three times

def back (len):
  turtle.penup()
  turtle.backward(len)
  turtle.pendown()
  
def square (size):
  for i in range (4):
   turtle.forward(size)
   turtle.left (90)

square(100)
back(75)
square(50)
back(50)
square(25)
