+++

title="Neželví grafika"

date=2021-03-21

+++

### Úloha 1.

```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(10, 100, 200, 100, 10, 200, 10,100)
```
### Úloha 2.
Ano, lze ho ještě nakreslit dvoumi různými způsoby. (pokud nebereme v potaz pořadí souřadnic)
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(110, 10, 10, 200, 210, 200)
canva.create_line(210, 200, 110, 10)
```
nebo

```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(10, 200, 210, 200, 110, 10)
canvas.create_line(110, 10, 10, 200)
```
a nebo

```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(210, 200, 110, 10, 10, 200)
canvas.create_line(10, 200, 210, 200)
```

### Úloha 3.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(110, 10, 10, 200, 210, 200, 110, 10, fill='blue')
canvas.create_line(160, 10, 60, 200, 260, 200, 160, 10, fill='red')
```
### Úloha 4.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(110, 10, 210, 200, width='10', fill='yellow')
canvas.create_line(110, 10, 210, 200, width='8', fill='blue')
canvas.create_line(110, 10, 210, 200, width='6', fill='red')
canvas.create_line(110, 10, 210, 200, width='4', fill='white')
canvas.create_line(110, 10, 210, 200, width='2', fill='green')
```

### Úloha 5.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
# L
canvas.create_line(10, 10, 10, 110, 60, 110)
# T
canvas.create_line(10, 10, 60, 10)
canvas.create_line(35, 10, 35, 110)
# H
canvas.create_line(10, 10, 10, 110)
canvas.create_line(10, 60, 60, 60)
canvas.create_line(60, 10, 60, 110)
# Z
canvas.create_line(10, 10, 60, 10, 10, 110, 60, 110)
```

### Úloha 6.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_line(10, 10, 10, 60, 110, 60, 110, 10, 10, 10)
```

### Úloha 7.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_rectangle(10, 50, 110, 100)
canvas.create_rectangle(110, 100, 210, 50)
```

### Úloha 8.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_rectangle(10, 50, 110, 100)
canvas.create_rectangle(110, 100, 210, 50)
canvas.create_rectangle(110, 100, 10, 150)
```

### Úloha 9.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_rectangle(10, 50, 110, 100, fill='blue', outline='green', width='5')
canvas.create_rectangle(110, 100, 210, 50, fill='yellow', outline='green', width='5')
canvas.create_rectangle(110, 100, 10, 150, fill='red', outline='green', width='5')
```

### Úloha 10.
```python
import tkinter
canvas = tkinter.Canvas()
canvas.pack()
canvas.create_rectangle(10, 50, 110, 100, fill='blue', outline='green', width='5')
canvas.create_rectangle(110, 100, 210, 50, fill='yellow', outline='green', width='5')
canvas.create_rectangle(110, 100, 10, 150, fill='red', outline='green', width='5')
canvas.create_rectangle(60, 125, 160, 75, fill='brown', outline='green', width='5')
```

