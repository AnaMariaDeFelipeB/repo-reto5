# Repostorio reto 5. 
### _Desarrollado por Ana Maria De Felipe Briñez._
---
Bienvenidos a este repostorio del reto 5 de la clase de programación, en este respostorio nos adentraremos más al mundo de la programación al crear diversos codigos en Python para resolver problemas planteados. 

Para comenzar iniciaremos con el primer problema planteado. 

1. **Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.**

Para resolver dicho problema, desarrolle el siguiente codigo en VScode. 

`Codigo para determinar si un número es una vocal en ASCCI.`

```Python
   n : int = int (input("Ingrese número entero: "))
if chr(n) =="a" or chr(n) =="A" or chr(n) =="E" or chr(n) =="e" or chr(n) =="i" or chr(n) =="I" or chr(n) =="o" or chr(n) =="O" or chr(n) =="u" or chr(n) =="U":
    print ("El número " + str(n) + " en ASCCI es una vocal. " +  "Es la vocal " + chr(n))
else: 
   print ("El número " + str(n) + " en ASCCI no es una vocal ")
print(chr(n))
```

Muestra del desarrollo. 

![image](https://user-images.githubusercontent.com/124607045/226121272-26e118f8-424a-41d6-9c12-144fa8bb867c.png)


No olvides revisar el archivo. 

---

Ahora bien, el segundo problema planteado es el siguiente.

2. **Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.**

`Codigo para determinar si el código ASCII de primera letra de la cadena es par o no.` 

```Python
s = input("Ingrese una palabra cualquiera, número o letra: ")
x = (ord(s[0]))
z = x%2
if z==0: 
    print("La primer letra de la cadena en ASCCI es un número par. ")
else: 
    print("La primer letra de la cadena en ASCCI es un número impar. ")
print("Su código en ASCII es " + str(x))
print("El caracter ingresado fue " + str(s))
```

Evidencia del desarrollo. 

![image](https://user-images.githubusercontent.com/124607045/226121317-e54d3908-2710-48ea-918e-c6730d3d91e4.png)

No olvides revisar el archivo. 

---

El tercer problema trata acerca de lo siguiente. 

3. **Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.**

`Codigo para determinar si un carácter es un dígito o no.` 
```Python
a = input("Ingrese caracter cualquiera: ")
x = (ord(a[0]))
if x>=0 and x<=9:
    print("El carácter " + str(a) + " es un digito.")
else: 
    print("El carácter " + str(a) + " no es un digito")
print(x)
```

Muestra del desarrollo. 

![image](https://user-images.githubusercontent.com/124607045/226121498-31b8756d-1c97-4621-8f5f-bf238d5d0481.png)

No olvides revisar el archivo. 

---

Por otro lado, encontramos el cuarto problema. 

4. **Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero.**

`Codigo para determinar si un número x real es positivo, negativo o cero.` 
```Python
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

No olvides revisar el archivo. 

---

El penúltimo problema es el siguiente, 

5. **Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.**

`Codigo para determinar si un punto R**2 pertenece al interior del circulo.`

```Python
radio:float=(input("Ingrese valor del radio: "))
x: float =(input("Ingrese coordenada en x del centro del circulo: "))
y: float =(input("Ingrese coordenada en y del centro del circulo: "))
a: float = (input("Ingrese coordenada x del punto: "))
b: float = (input("Ingrese coordenada y del punto:  "))

operación1: float = a-x
operación2: float = operación1 **2 
operación3: float = b-y
operación4: float = operación3**2 
operación5: float = operación2 + operación4
operación6: float = operación5**5
resultado: float == operación6

if resultado<radio: 
    print("La coordenada " + "(" + str(a) + "," + str(b) + ")" + " se encuentra dentro del circulo con centro en " + "(" + str(x) + "," + str(y) + ")" " y un radio de " + str(radio))
else: 
    print(print("La coordenada " + "(" + str(a) + "," + str(b) + ")" + " se encuentra afuera del circulo con centro en " + "(" + str(x) + "," + str(y) + ")" " y un radio de " + str(radio)))
```
No olvides revisar archivo. 

---

Finalmente, llegamos al último problema que consiste en lo siguiente. 

6. **Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.**

`Codigo para determinar si un triángulo exite.` 

```Python
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
