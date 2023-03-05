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

---

Por otro lado, encontramos el cuarto problema. 

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

[![Problema4.jpg](https://i.postimg.cc/2ypbBQ1p/Problema4.jpg)](https://postimg.cc/0Mf2TJGZ)
---
Finalmente, llegamos al último problema que consiste en lo siguiente. 

6. **Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.**

`Codigo para determinar si un triángulo exite.` 

```pseudocode
a : float = float(input("Ingrese la longitud #1 de su triángulo: ")) 
b : float = float(input("Ingrese la longitud #2 de su triángulo: "))
c : float = float(input("Ingrese la longitud #3 de su triángulo: "))

if a+b > c  and b+c > a and a+c > b: 
    print("Con las longitudes " + str(a) +  ", " + str(b) + ", " + str(c) + " se puede construir un triángulo.") 
else:
    print("Con las longitudes " + str(a) +  ", " + str(b) + ", " + str(c) + " NO se puede construir un triángulo.")
```

Evidencia del desarrollo: 

[![Problema6.jpg](https://i.postimg.cc/mgGrNZZ9/Problema6.jpg)](https://postimg.cc/QH0sj3TN)

Esto fue todo por el momento. Byee.
