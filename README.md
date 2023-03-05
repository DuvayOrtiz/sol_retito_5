# sol_retito_5
## programando y llorando ando

En este repo estaremos desarrollando el reto 5
### punto 1
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```pseudocode
x = int
x = int(input("ingrese un numero entero: "))
if x == 97 or x == 101 or x == 105 or x == 111 or x == 117  :
    print ("pertenece a la vocal  "   +   chr(x))
else: 
    print("eso no esta en el codigo ASCII como vocal minuscula")


```

### punto 2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```pseudocode
x = 'e'
a=float
x=str
x=str(input("introducir una letra: "))
a = ord(x) 
if a%2==0:
    print("la letra pertenece a un par del ASCII")
else:
    print("la letra no pertenece a un par del ASCII")    


```

### punto 3

Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```pseudocode

x=int
x=int(input("introducir un digito: "))
if x>=0 and x<=9 :
    print("es un digito")
else:
    print("no es un digito")    


```

### punto 4

Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. 

```pseudocode

x=float
x=float(input("escribir un real: "))
if x==0:
    print("El número x es el neutro para la suma")
elif x>0:
    print("El número x es positivo")
elif x<0:
    print("El número x es negativo")

```


### punto 5

Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```pseudocode

x=float
y=float
r=float
r=float(input("digitar el radio: "))
x=float(input("digitar x: "))
y=float(input("digitar y: "))
if (x*x + y*y > r**2):
    print("esta por fuera de la circunferencia de radio  " + str(r))
elif (x*x + y*y  == r**2):
    print("esta justo sobre la circunferencia de radio  " + str(r))
else:
    print("esta dentro de la circunferencia")  


```


### punto 6

Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```pseudocode
a=float
b=float
c=float
a=float(input("longitud del lado 1: "))
b=float(input("longitud del lado 2: "))
c=float(input("longitud del lado 3: "))
if a+b>c and a+c>b and b+c>a:
    print("se puede hacer el triangulo")
else:
    print("no se puede hacer el triangulo")   


```


