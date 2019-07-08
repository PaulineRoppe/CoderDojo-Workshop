![Logo CoderDojo](./images/coderdojo-logo.png)

## Apprends les bases de la programmation

###  Exercice Python - Course de tortues


<pre><code># vous importez turtle de python
from turtle import *

# ceci c'est pour que la course soit aléatoire
from random import randint

# ceci est une boucle pour créer la piste pour la course
for step in range(15):
    write(step, align = 'center')
    pendown()
    right(90)
    forward(150)
    penup()
    backward(150)
    left(90)
    forward(20)

# ici c'est pour replacer la flèche à 0 et le hideturtle() c'est pour enlever la flèche
penup()
goto(0,0)
pendown()
hideturtle()

# ici vous allez créer vos 5 variables
bob = Turtle()
bob.color('yellow')
bob.shape('turtle')
bob.penup()
bob.goto(-20,-10) # c'est pour positionnée votre tortue
bob.pendown()

patrick = Turtle()
patrick.color('pink')
patrick.shape('turtle')
patrick.penup()
patrick.goto(-20,-40)# c'est pour positionnée votre tortue
patrick.pendown()

carlo = Turtle()
carlo.color('lightblue')
carlo.shape('turtle')
carlo.penup()

carlo.goto(-20,-70)# c'est pour positionnée votre tortue
carlo.pendown()

crab = Turtle()
crab.color('red')
crab.shape('turtle')
crab.penup()
crab.goto(-20,-100)# c'est pour positionnée votre tortue
crab.pendown()

gary = Turtle()
gary.color('lightgreen')
gary.shape('turtle')
gary.penup()
gary.goto(-20,-130)# c'est pour positionnée votre tortue
gary.pendown()

# cette boucle c'est pour faire tourner vos tortues chacune leur tour à 360°
for turn in range(2):
    bob.right(360)
    patrick.left(360)
    carlo.right(360)
    crab.left(360)
    gary.right(360)

# la dernière boucle est pour commencer la course des tortues et le randint c'est ce que vous avez importé au début ce qui permet de faire une course aléatoire
for turn in range(100):
    bob.forward(randint(1,5))
    patrick.forward(randint(1,5))
    carlo.forward(randint(1,5))
    crab.forward(randint(1,5))
    gary.forward(randint(1,5))
</code></pre>

### [Solution de l'exercice](https://github.com/PaulineRoppe/CoderDojo-Workshop/blob/master/soluce-python.md)
### [Retour à la page "technologies"](https://github.com/PaulineRoppe/CoderDojo-Workshop/blob/master/technologies.md)
