# Repostorio reto 5. 
### _Desarrollado por Ana Maria De Felipe Briñez._
---
Bienvenidos a este repostorio del reto 5 de la clase de programación, en este respostorio nos adentraremos más al mundo de la programación al crear diversos codigos en Python para resolver problemas planteados. 

Para comenzar iniciaremos con el primer problema planteado. 

1. **Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.**

Para resolver dicho problema, desarrolle el siguiente codigo en VScode. 

`Codigo para determinar si un número es una vocal en ASCCI.`

```pseudocode
  n : int = int (input("Ingrese número entero: "))
if chr(n) =="a" or chr(n) =="A" or chr(n) =="E" or chr(n) =="e" or chr(n) =="i" or chr(n) =="I" or chr(n) =="o" or chr(n) =="O" or chr(n) =="u" or chr(n) =="U":
    print ("El número " + str(n) + " en ASCCI es una vocal. " +  "Es la vocal " + chr(n))
print(chr(n))
```

Muestra del desarrollo. 

[![Problema1.png](https://i.postimg.cc/DfBrWsBD/Problema1.png)](https://postimg.cc/py5h49NY)
---

Ahora bien, el segundo problema planteado es el siguiente.

2. **Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.**

`Codigo para determinar si el código ASCII de primera letra de la cadena es par o no.` 

```pseudocode
s = input("Ingrese una palabra cualquiera: ")
x = (ord(s[0]))
z = x%2
if z==0: 
    print("La primer letra de la cadena en ASCCI es un número par. ")
else: 
    print("La primer letra de la cadena en ASCCI es un número impar. ")
print(x)
```

Evidencia del desarrollo. 

[![problema2.jpg](https://i.postimg.cc/qRfMgNVF/problema2.jpg)](https://postimg.cc/bGTjBNv0)

---

El tercer problema trata acerca de lo siguiente. 

3. **Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.**

`Codigo para determinar si un carácter es un dígito o no.` 
```pseudocode
  
```

Muestra del desarrollo. 

---

Por otro lado, encontramos el cuarto problema. 

4. **Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero.**

`Codigo para determinar si un número x real es positivo, negativo o cero.` 
```pseudocode
  n: float = float(input("Inserte número real: "))
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

El penúltimo problema es el siguiente, 

3. **Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.**

`Codigo para determinar si un punto R**2 pertenece al interior del circulo.`

```pseudocode
  
```

Aquí se puede evidenciar el funcionamiento del codigo. 

LINK

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

---

### Esto fue todo por el momento. Byee.
