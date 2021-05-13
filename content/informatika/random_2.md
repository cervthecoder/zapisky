+++
title = "Náhoda v pythonu 2."
date = 2021-05-12
+++

```python
import random
import tkinter

def nakup():
    ceny = [random.randint(100,300) for i in range(3)]
    for cena in ceny:
        print(f'Tvůj {ceny.index(cena)}. nákup stál {cena} korun')
    print(f'Celkem jsi zaplatil {sum(ceny)} korun')

def baliky():
    canvas = tkinter.Canvas()
    canvas.pack()
    canvas.create_rectangle(0, 0, 100, random.randint(10,200), fill="green")
    canvas.create_rectangle(100, 0, 200, random.randint(10,200), fill="red")
    canvas.create_rectangle(200, 0, 300, random.randint(10, 200), fill="blue")

def okraje():
    canvas = tkinter.Canvas()
    canvas.pack()
    canvas.create_text(0, 50, text="Levý okraj")
    canvas.create_text(50, 0, text="Horní okraj")
    canvas.create_text(50, 100, text="Dolní okraj")
    canvas.create_text(100, 50, text=="Pravý okraj")

def vrcholy_obdelniku():
    canvas = tkinter
    canvas.pack()
    canvas.create_rectangle(100, 100, 200, 300)
    canvas.create_text(100, 100, text="D")
    canvas.create_text(100, 300, text="A")
    canvas.create_text(200, 100, text="C")
    canvas.create_text(200, 300, text="B")

def vrcholy_obdelniku_():
    canvas = tkinter
    canvas.pack()
    canvas.create_rectangle(100, 100, 200, 300)
    canvas.create_text(90, 90, text="D")
    canvas.create_text(90, 310, text="A")
    canvas.create_text(210, 90, text="C")
    canvas.create_text(210, 310, text="B")

def pisnicka():
    canvas = tkinter
    canvas.pack()
    canvas.create_text(50, 100, text="Load up on guns, bring your friends")
    canvas.create_text(50, 90, text="It's fun to lose and to pretend")
    canvas.create_text(50, 80, text="She's over-bored and self-assured")
    canvas.create_text(50, 70, text="Oh no, I know a dirty word")

def stitek(x, y):
    canvas = tkinter
    canvas.pack()
    canvas.create_text(x, y, text="Matěj")
    canvas.create_rectangle()

def den():
    canvas.create_text(random.randint(180, 260), 40, text='den')
    canvas.create_text(random.randint(80, 110), 50, text='je')
    canvas.create_text(random.randint(120, 170), 70, text='pěkný')
    canvas.create_text(random.randint(30, 70), 60, text='dnes')
# Dnes je pěkný den

def nah_cislo_grafika():
    canvas.create_text(random.randint(0, 100), random.randint(0, 100), text=f"{random.randint(100000, 9999999)}")
```
