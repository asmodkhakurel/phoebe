# phoebe
It contains code to draw the name "PHOEBE" using python turtle.

import turtle

wn = turtle.Screen()
phoebe = turtle.Turtle()

wn.bgcolor("yellow")

phoebe.shape("turtle")
phoebe.color("purple")

phoebe.left(90)
phoebe.forward(100)
phoebe.right(90)
phoebe.circle(-30, 180)

phoebe.up()

phoebe.goto(50,0)
phoebe.down()
phoebe.right(90)
phoebe.forward(100)
phoebe.forward(-50)
phoebe.right(90)
phoebe.forward(50)
phoebe.left(90)
phoebe.forward(50)
phoebe.forward(-100)
phoebe.up()

phoebe.goto(175,0)
phoebe.down()
phoebe.right(90)
phoebe.circle(50)

phoebe.up()

phoebe.goto(250,0)
phoebe.down()
phoebe.forward(50)
phoebe.forward(-50)
phoebe.left(90)
phoebe.forward(50)
phoebe.right(90)
phoebe.forward(50)
phoebe.forward(-50)
phoebe.left(90)
phoebe.forward(50)
phoebe.right(90)
phoebe.forward(50)

phoebe.up()
phoebe.goto(325,0)
phoebe.down()
phoebe.circle(25,180)
phoebe.right(180)
phoebe.circle(25,180)
phoebe.left(90)
phoebe.forward(100)

phoebe.up()
phoebe.goto(375,0)
phoebe.left(90)
phoebe.down()
phoebe.forward(50)
phoebe.forward(-50)
phoebe.left(90)
phoebe.forward(50)
phoebe.right(90)
phoebe.forward(50)
phoebe.forward(-50)
phoebe.left(90)
phoebe.forward(50)
phoebe.right(90)
phoebe.forward(50)
