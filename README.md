# Repostorio reto 5. 
### _Desarrollado por Ana Maria De Felipe Briñez._
---
Bienvenidos a este repostorio del reto 5 de la clase de programación, en este respostorio nos adentraremos más al mundo de la programación al crear diversos codigos en Python para resolver problemas planteados. 

Para comenzar iniciaremos con el primer problema planteado. 
1. **Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.**

Para resolver dicho problema, desarrolle el siguiente codigo en VScode. 

`Codigo para determinar si un número es una vocal en ASCCI.` 
```pseudocode
  n : int = int (input("Ingrese número entero "))
if chr(n) =="a" or chr(n) =="A" or chr(n) =="E" or chr(n) =="e" or chr(n) =="i" or chr(n) =="I" or chr(n) =="o" or chr(n) =="O" or chr(n) =="u" or chr(n) =="U":
    print ("El número " + str(n) + " en ASCCI es una vocal. " +  "Es la vocal " + chr(n))
print(chr(n))
```

Muestra del desarrollo. 

[![Problema1.png](https://i.postimg.cc/DfBrWsBD/Problema1.png)](https://postimg.cc/py5h49NY)
---
Ahora bien, el segundo problema planteado es el siguiente.

4. **Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero.**

`Codigo para determinar si un número x real es positivo, negativo o cero.` 
```pseudocode
  n: float = float(input("Inserte número real "))
if n > 0: 
    print("El número " + str(n)+ " es un número positivo.")
elif n == 0: 
    print("El número " + str(n)+ " es el neutro para la suma.")
elif n<0: 
    print("el número " + str(n) + " es un número negativo.")
```

Muestra del desarrollo. 

[![Problema4.png](https://i.postimg.cc/QCqPWqfV/Problema4.png)](https://postimg.cc/N25b3Rqw)

