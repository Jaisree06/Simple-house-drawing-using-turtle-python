Simple House Drawing using Python Turtle:

This project is a beginner-level Python program that uses the Turtle graphics module to draw a simple, colorful house. It demonstrates basic turtle movements, fill colors, loops, and geometric shapes to simulate a house structure. The design includes a roof, walls, door, and surrounding ground using various turtle commands.


Coding:

import turtle
# Create the screen and turtle object
wn = turtle.Screen()
elex = turtle.Turtle()
# Draw the roof
elex.fillcolor("brown")
elex.begin_fill()
elex.forward(80)
elex.left(125)
elex.forward(80)
elex.left(118)
elex.forward(75)
elex.end_fill()
# Draw the house body
elex.fillcolor("Yellow")
elex.begin_fill()
elex.left(27)
elex.forward(180)
elex.left(90)
elex.forward(80)
elex.left(90)
elex.forward(180)
elex.end_fill()
# Add layering or background fill
elex.fillcolor("yellow")
elex.begin_fill()
for i in range(5):
    elex.right(90)
    elex.forward(180)
elex.left(110)
elex.forward(70)
elex.left(70)
elex.forward(210)
elex.end_fill()
# Reverse to original position
elex.backward(210)
elex.right(70)
elex.backward(70)
elex.right(110)
elex.backward(180)
elex.left(90)
elex.backward(180)
# Draw door
elex.left(90)
elex.forward(30)
elex.right(90)
elex.forward(100)
elex.right(270)
elex.forward(35)
elex.left(90)
elex.forward(100)
elex.right(270)
elex.forward(250)
# Draw ground or grass
elex.fillcolor("green")
elex.begin_fill()
elex.right(90)
elex.forward(30)
elex.left(270)
elex.forward(300)
elex.right(90)
elex.forward(30)
elex.right(90)
elex.forward(40)
elex.end_fill()


