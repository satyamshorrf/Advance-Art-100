# Advance-Art-100
#Create python use import turtle graphics code
#Author - Satyam Shorrf 
from turtle import*
import colorsys as cr
title('Satyam Shorrf ')
setup(width=550, height=650)
bgcolor('black')
tracer(2)
c=10
pensize(4)

for i in range(200):
  p = cr.hsv_to_rgb(c,1,1)
  c+0.007
  goto(0,0)
  pencolor(p)
  left(150)
  forward(270-i)
  left(250)
  right(160)
  circle(17,50)
  forward(190)
  right(90)
  forward(i)
  left(100)
done()  
