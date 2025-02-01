# ejercicio_6

### main.py

```python
def desglose_euros(cantidad):
    billetes_monedas = [500, 200, 100, 50, 20, 10, 5, 2, 1]
    desglose = {}
    for valor in billetes_monedas:
        if cantidad >= valor:
            desglose[valor] = cantidad // valor
            cantidad %= valor
    return desglose

if __name__ == "__main__":
    # Solicitar cantidad al usuario y comprobar que es un número entero
    try:
        cantidad = int(input("Introduce la cantidad en euros: "))
        desglose = desglose_euros(cantidad)
        print("Desglose en billetes y monedas:")
        for valor, cantidad in desglose.items():
            print(f"{cantidad} de {valor}€")
    except ValueError:
        print("Por favor, introduce un número entero válido.")
```

### Rama 1: `desglose_euros`

```python
def desglose_euros(cantidad):
    billetes_monedas = [500, 200, 100, 50, 20, 10, 5, 2, 1]
    desglose = {}
    for valor in billetes_monedas:
        if cantidad >= valor:
            desglose[valor] = cantidad // valor
            cantidad %= valor
    return desglose
```

### Rama 2: `solicitar_cantidad`

```python
if __name__ == "__main__":
    # Solicitar cantidad al usuario y comprobar que es un número entero
    try:
        cantidad = int(input("Introduce la cantidad en euros: "))
        desglose = desglose_euros(cantidad)
        print("Desglose en billetes y monedas:")
        for valor, cantidad in desglose.items():
            print(f"{cantidad} de {valor}€")
    except ValueError:
        print("Por favor, introduce un número entero válido.")

def desglose_euros(cantidad):
    billetes_monedas = [500, 200, 100, 50, 20, 10, 5, 2, 1]
    desglose = {}
    for valor in billetes_monedas:
        if cantidad >= valor:
            desglose[valor] = cantidad // valor
            cantidad %= valor
    return desglose
```

### Rama 3: `funciones_generales`

```python
def desglose_euros(cantidad):
    billetes_monedas = [500, 200, 100, 50, 20, 10, 5, 2, 1]
    desglose = {}
    for valor in billetes_monedas:
        if cantidad >= valor:
            desglose[valor] = cantidad // valor
            cantidad %= valor
    return desglose

if __name__ == "__main__":
    # Solicitar cantidad al usuario y comprobar que es un número entero
    try:
        cantidad = int(input("Introduce la cantidad en euros: "))
        desglose = desglose_euros(cantidad)
        print("Desglose en billetes y monedas:")
        for valor, cantidad in desglose.items():
            print(f"{cantidad} de {valor}€")
    except ValueError:
        print("Por favor, introduce un número entero válido.")
```

