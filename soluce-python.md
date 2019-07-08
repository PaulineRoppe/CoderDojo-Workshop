![Logo CoderDojo](./images/coderdojo-logo.png)

## Apprends les bases de la programmation

### Solution Python - Course de tortues

<pre><code>from turtle import *
from random import randint

for step in range(15):
    write(step, align = 'center')
    pendown()
    right(90)
    forward(150)
    penup()
    backward(150)
    left(90)
    forward(20)

speed(10)
penup()
goto(0,0)
pendown()
hideturtle()

bob = Turtle()
bob.color('yellow')
bob.shape('turtle')
bob.penup()
bob.goto(-20,-10)
bob.pendown()

patrick = Turtle()
patrick.color('pink')
patrick.shape('turtle')
patrick.penup()
patrick.goto(-20,-40)
patrick.pendown()

carlo = Turtle()
carlo.color('lightblue')
carlo.shape('turtle')
carlo.penup()
carlo.goto(-20,-70)
carlo.pendown()

crab = Turtle()
crab.color('red')
crab.shape('turtle')
crab.penup()
crab.goto(-20,-100)
crab.pendown()

gary = Turtle()
gary.color('lightgreen')
gary.shape('turtle')
gary.penup()
gary.goto(-20,-130)
gary.pendown()

for turn in range(2):
    bob.right(360)
    patrick.left(360)
    carlo.right(360)
    crab.left(360)
    gary.right(360)

for turn in range(100):
    bob.forward(randint(1,5))
    patrick.forward(randint(1,5))
    carlo.forward(randint(1,5))
    crab.forward(randint(1,5))
    gary.forward(randint(1,5))
    </code></pre>
    
    ### [Retour à la page "technologies"](https://github.com/PaulineRoppe/CoderDojo-Workshop/blob/master/technologies.md)
