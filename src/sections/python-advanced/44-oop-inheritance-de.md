# OOP: Vererbung

## Unterklassen und Vererbungsreihenfolge

## super()

Proxy zu den Elternklassen

## super()

ohne super:

```py
class Child(A, B):
    def __init__(self):
        A.__init__(self)
        B.__init__(self)
```

## super()

Mit super:

```py
class Child(A, B):
    def __init__(self):
        super().__init__()
```