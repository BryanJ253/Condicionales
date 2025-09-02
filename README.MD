# Ejercicios de condicionales
## Bryan Felipe Jaime Diaz
### Explicacion del codigo
#### Con este ejercicio se busca practicar los condicionales if y else, por lo que se propone hacer un codigo en el cual se píde ingresar un numero por consola y con los condicionales determinar si cumplen o no con los operadores de comparacion (>, <, >=, <=, ==, !=) con respecto al numero 5.
```py
# Almacenamos un dato ingresado por consola en una variable
A = float(input("Ingrese un numero para evaluarlo: "))
# Evaluamos el dato ingresado para ver si es mayor que 5
if A > 5:
    print(f"El numero {A} es mayor que 5")
else:
    print(f"El numero {A} no es mayor que 5")
# Evaluamos el dato ingresado para ver si es menor que 5
if A < 5:
    print(f"El numero {A} es menor que 5")
else:
    print(f"El numero {A} no es menor que 5")
# Evaluamos el dato ingresado para ver si es mayor o igual que 5
if A >= 5:
    print(f"El numero {A} es mayor o igual que 5")
else:
    print(f"El numero {A} no es mayor ni igual a 5")
# Evaluamos el dato ingresado para ver si es menor o igual que 5
if A <= 5:
    print(f"El numero {A} es menor o igual que 5")
else:
    print(f"El numero {A} no es menor ni igual a 5")
# Evaluamos el dato ingresado para ver si es exactamente igual que 5
if A == 5:
    print(f"El numero {A} es igual a 5")
else:
    print(f"El numero {A} no es igual a 5")
# Evaluamos el dato ingresado para ver si es diferente de 5
if A != 5:
    print(f"El numero {A} es diferente a 5")
else:
    print(f"El numero {A} no es diferente a 5")

<img width="1173" height="552" alt="image" src="https://github.com/BryanJ253/Condicionales/blob/673a16c074c202aff1d3c04eb64e2a6d4c7f13ca/image-2.png?raw=true" />
