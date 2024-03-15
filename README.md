# Reto_4
>### 1.Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
n : int = int(input("Numero entero: "))
if n == 97 or n == 101 or n == 105 or n == 111 or n == 117 : #97=a, 101=e, 105=i, 111=0, 117=u
    print(str(n)+ " corresponde al código ASCII de la vocal minúscula: "+ chr(n))
else :
    print(str(n) + " no corresponde al código ASCII de una vocal minúscula")
```
>### 2.Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python
n = ord(input("Cadena de longitud 1"))
if n%2 == 0 :
    print("El código ASCII de la primera letra de la cadena es par")
else :
    print("el código ASCII de la primera letra de la cadena no es par")
```
>### 3.Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
n = ord(input("Un caracter"))
if n>=48 and n<=57 :
		print("El caracter es un digito")
else :
    print("El carácter no es un digito")
```
>### 4.Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
> Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
```python
x : float = float(input("Ingrese número real"))
if x > 0 :
    print("El número x es positivo")
elif x < 0 :
    print("El número x es negativo")
else :
    print("El número x es el neutro para la suma")
```
>### 5.Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python
punto_x :float  = float(input("coordenada de punto en x: "))
punto_y : float = float(input("coordenada de punto en y: "))
centro_x : float = float(input("Centro del cirulo en x: "))
centro_y : float = float(input("Centro de circulo en y: "))
radio : float =  float(input("Radio del circulo: "))
if (punto_x-centro_x)**2 + (punto_y-centro_y)**2 < radio**2 : 
    print("El punto pertenece al interior del circulo")
else :
    print("El punto no  pertenece al interior del circulo")

```
>### 6.Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
lado_1 : int = int(input("Longitud positiva del lado 1"))
lado_2 : int = int(input("Longitud positiva del lado 2"))
lado_3 : int = int(input("Longitud positiva del lado 3"))
if lado_1 + lado_2 >lado_3 :
    print("se puede construir un triangulo")
else :
    print("No se puede construir un triangulo")
```
