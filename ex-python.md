![Logo CoderDojo](./images/coderdojo-logo.png)

## Apprends les bases de la programmation

###  Exercice Python - Course de tortues

Tu dois d'abord installer Python3 sur ton PC, pour cela fais :

<code>sudo apt-get install python3.6</code><br/>
<code>sudo apt-get install idle-python3.6</code><br/>
<br/>
 Recherche ensuite "idle" dans les programmes installés sur ton PC et lance-le
 Tu peux commencer l'exercice, tape ligne par ligne et boucle par boucle pour voir l'évolution de ton code dans l'interface graphique de Turtle.

1.Importe Turtle dans Python

<pre><code>from turtle import *</code></pre>

2.Importe le module qui gère l'aléatoire

<pre><code>from random import randint</code></pre>

3.Voici la boucle qui sert à créer la piste de course des tortues (faire un copier-coller)

<pre><code>
for step in range(15):
    write(step, align = 'center')
    pendown()
    right(90)
    forward(150)
    penup()
    backward(150)
    left(90)
    forward(20)
</code></pre>

4.Fais ceci pour replacer la flèche à 0 et pour la cacher.

<pre><code>
penup()
goto(0,0)
pendown()
hideturtle()
</code></pre>

5.Crée une variable (ceci correspond à une tortue)
  Crées 5 tortues avec des noms différents.
  
<pre><code>  
bob = Turtle()
bob.penup()
bob.goto(-20,-10)
bob.pendown()
</code></pre>

6.Dans les variables que tu viens de créer, ajoute une couleur et la forme de tortue 
  (voir feuille mémo en bas de page)

7.Crée une petite animation pour chaque tortue
  Elles doivent chacune faire 2 tours sur elles-mêmes dans le sens de ton choix

8.Crée ensuite une dernère boucle qui permettra la course aléatoire des tortues
  Elles doivent chacune avancer de 100 pas


### Aide mémoire turtle :

![PDF aide mémoire Turtle](./images/python/turtle.pdf)

### [Retour à la page "technologies"](https://github.com/PaulineRoppe/CoderDojo-Workshop/blob/master/technologies.md)
