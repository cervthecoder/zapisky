+++

title="Random v pythonu"

date=2021-04-25

+++

```python
import random
import tkinter
def cara():
    print('+--+--+--+--+--+--+')

def hulky():
    print('|  |  |  |  |  |  |')

'''
cara()
hulky()
cara()
hulky()
cara()
'''

def ctvereckovy_papir(rows): # zobrazí určitý počet řádků
    cara()
    for i in range(rows):
        hulky()
        cara()

'''
ctvereckovy_papir(4)
'''

'''
n = random.randint(1, 6)
print(f'Na kostce padla {n}')
'''

def hod_kostkou():
    n = random.randint(1, 6)
    print(f'Na kostce padla {n}')

def dice_20():
    n = random.randint(1, 20)
    print(f'Na kostce padla {n}')

def binary_dice():
    sides = [0 for n in range(3)] + [1 for i in range(3)]
    print(f'Na kostce padla {random.choice(sides)}')

def even_dice():
    sides = [n for n in range(12) if n % 2 ==0]
    print(f'Na kostce padla {random.choice(sides)}')

def odd_dice():
    sides = [n for n in range(12) if n % 2 ==1]
    print(f'Na kostce padla {random.choice(sides)}')

def square_dice():
    sides = [n^2 for n in range(6)]
    print(f'Na kostce padla {random.choice(sides)}')

def prepoved():
    print(f'Dnes bude {random.randint(-15, 35)} stupňů')

def pin(digits): # digits znamená kolika místný bude pin
    print('Tvůj nový PIN je'.join([random.randint(0, 9) for i in range(digits)]))

def datum():
    print(f'Pokoj si uklidím {random.randint(1, 30)} . {random.randint(1, 12)} . 2021')

def nahodny_ctverec(how_many): # how_many znamená kolik chceš nakreslit čtverců
    canvas = tkinter.Canvas()
    canvas.pack()
    for i in range(how_many):
        x = random.randint(10, 300)
        y = random.randint(10, 200)
        canvas.create_rectangle(x, y, x+random.randint(10, 100), y+random.randint(10, 100))
    
def sportovni_vlajka():
    x = random.randint(10, 300)
    y = random.randint(10, 200)
    canvas = tkinter.Canvas()
    canvas.pack()
    canvas.create_rectangle(0, 0, x, y, fill='green')
    canvas.create_rectangle(0, 200, x, y, fill='orange')
    canvas.create_rectangle(300, 200, x, y, fill='blue')
    canvas.create_rectangle(300, 0, x, y, fill='yellow')

```

