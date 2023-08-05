# spiderman
#I made spider man logo by turtle module
import turtle

# l = left
# r = right
# u = upper
# l = lower
# f = first
# s = second
# l = leg

#import the screen
turtle.Screen()
turtle.hideturtle()
turtle.title("first pc programing by srour XD")
turtle.setup(800, 600)
turtle.bgcolor("red")
turtle.tracer(0)

#build the head
head = turtle.Turtle()
head.penup()
head.goto( 0, 0)
head.shape("circle")
head.shapesize(2.5)
head.color("black")
head.speed(0)
#build the Centuries
Centuries = turtle.Turtle()
Centuries.penup()
Centuries.goto(-2 , 7)
Centuries.shapesize(2.5)
Centuries.color("black")
Centuries.shape("turtle")
Centuries.speed(0)
#build body_1
body_1 = turtle.Turtle()
body_1.hideturtle()
body_1.goto(0 ,-20)
body_1.pensize(5)
body_1.begin_fill()
body_1.forward(20)
body_1.circle(-65 , 35)
body_1.left(-80)
body_1.forward(116)
body_1.left(50)
body_1.backward(120)
body_1.end_fill()

#build body_2
body_2 = turtle.Turtle()
body_2.hideturtle()
body_2.goto(0 ,-20)
body_2.pensize(5)
body_2.begin_fill()
body_2.forward(-20)
body_2.circle(-66 , -35)
body_2.left(-94)
body_2.forward(123)
body_2.left(-30)
body_2.backward(120)
body_2.end_fill()

#build the r_u_f_l
r_u_f_l = turtle.Turtle()
r_u_f_l.hideturtle()
r_u_f_l.goto(20 ,-10)
r_u_f_l.pensize(8)
r_u_f_l.begin_fill()
r_u_f_l.left(45)
r_u_f_l.forward(125)
r_u_f_l.left(90)
r_u_f_l.circle(120 , 30)

#build the r_u_s_l
r_u_s_l = turtle.Turtle()
r_u_s_l.hideturtle()
r_u_s_l.goto(20 ,-10)
r_u_s_l.pensize(8)
r_u_s_l.begin_fill()
r_u_s_l.left(5)
r_u_s_l.forward(100)
r_u_s_l.left(90)
r_u_s_l.circle(120 , 18)

#build the r_l_f_l
r_l_f_l = turtle.Turtle()
r_l_f_l.hideturtle()
r_l_f_l.goto(20 ,-10)
r_l_f_l.pensize(8)
r_l_f_l.begin_fill()
r_l_f_l.left(-28)
r_l_f_l.forward(125)
r_l_f_l.left(-90)
r_l_f_l.circle(-360 , 20)

#build the r_l_s_l
r_l_s_l = turtle.Turtle()
r_l_s_l.hideturtle()
r_l_s_l.goto(20 ,-10)
r_l_s_l.pensize(8)
r_l_s_l.begin_fill()
r_l_s_l.left(-60)
r_l_s_l.forward(110)
r_l_s_l.left(-90)
r_l_s_l.circle(-120 , 17.5)

#build the l_u_f_l
l_u_f_l = turtle.Turtle()
l_u_f_l.hideturtle()
l_u_f_l.goto(-20 ,-10)
l_u_f_l.pensize(8)
l_u_f_l.begin_fill()
l_u_f_l.left(135)
l_u_f_l.forward(125)
l_u_f_l.left(-90)
l_u_f_l.circle(-120 , 30)

#build the l_u_s_l
l_u_s_l = turtle.Turtle()
l_u_s_l.hideturtle()
l_u_s_l.goto(-20 ,-10)
l_u_s_l.pensize(8)
l_u_s_l.begin_fill()
l_u_s_l.left(175)
l_u_s_l.forward(100)
l_u_s_l.left(-90)
l_u_s_l.circle(-120 , 18)

#build the l_l_f_l
l_l_f_l = turtle.Turtle()
l_l_f_l.hideturtle()
l_l_f_l.goto(-20 ,-10)
l_l_f_l.pensize(8)
l_l_f_l.begin_fill()
l_l_f_l.left(208)
l_l_f_l.forward(125)
l_l_f_l.left(90)
l_l_f_l.circle(360 , 20)

#build the l_l_s_l
l_l_s_l = turtle.Turtle()
l_l_s_l.hideturtle()
l_l_s_l.goto(-20 ,-10)
l_l_s_l.pensize(8)
l_l_s_l.begin_fill()
l_l_s_l.left(240)
l_l_s_l.forward(110)
l_l_s_l.left(90)
l_l_s_l.circle(120 , 17.5)

while True:
    turtle.update()
