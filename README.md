# JavaScript-Basic

[Curso Básico de JavaScript](https://platzi.com/cursos/basico-javascript/)

## ¿Que tipos por default son verdaderos y falsos?

Usamos la función de JS que es Boolean() dentro del paréntesis ponemos el valor y nos dice si el mismo el False o True.

### Falsy

- Boolean() —> sin ningun valor es false
- Boolean(0) —> **FALSE**
- Boolean(null) —> **FALSE**
- Boolean(NaN) —> **FALSE** // NaN es Not and Number
- Boolean(Undefined) —> **FALSE**
- Boolean(false) —> **FALSE**
- Boolean("") —> **FALSE**

### Truthy
- Boolean(1) —> **TRUE** //cualquier numero que no sea igual a cero es true
- Boolean(“a”) —> **TRUE**
- Boolean(" ") —> **TRUE** // siendo un espacio el valor es true
- Boolean([]) —> **TRUE** // un array nos da un true
- Boolean({}) —> **TRUE** // un objeto nos da el valor de true
- Boolean(function() {}) —> **TRUE** //una funcion tambien es true
- Boolean(true) —> **TRUE**

Todo esto lo vamos a usar en condiciones esto valida si es verdadero o falso para ejecutar cierta acción.

## OPERADORES

### ARITMETICOS
**+** // Suma a + b,  afirmación unitaria +a : Positivo, concatenación "a" + "la" : "ala"

**-** // Resta a - b, negación unitaria -a : Negativo

 * // Producto a * b

/ // Divisor a / b

% // Residuo a % b

** // Potencia a ** b, a elevado a b

++ // Incremento (suma uno) a++ : a = a + 1

-- // Decremento (resta uno) a-- : a = a - 1

### ASIGNACIÓN
= // Asignación a = b

+= // Asignación de adición  a += b : a = a + b

-= // Asignación de sustracción  a -= b : a = a - b

*= // Asignación de multiplicación  a *= b : a = a * b

/= // Asignación de división  a /= b : a = a / b

%= // Asignación de residuo  a %= b : a = a % b

**= // Asignación de potencia  a **= b : a = a ** b

<<= // Asignación de desplazamiento a la izquierda  a <<= b : a = a << b

**>>=** // Asignación de desplazamiento a la derecha  a >>= b : a = a >> b

**>>>=** // Asignación sin signo de desplazamiento a la derecha  a >>>= b : a = a >>> b

&= // Asignación AND  a &= b : a = a & b

^= // Asignación XOR  a ^= b : a = a ^ b

|= // Asignación OR  a |= b : a = a | b

### COMPARACIÓN
== // Igualdad a == b, a tiene el mismo valor que b
!= // Distinto a != b, a tiene un valor diferente a b
=== // Identidad a === b igual valor igual tipo de dato
!== // Sin Identidad a !== b igual valor o igual tipo de dato
> // Mayor que a > b
>= // Mayor o igual que a >= b
< // Menor que a < b
<= // Menor o igual que a <= b

### LOGICOS
&& // AND, Y, a && b : a y b
|| // OR, O, a || b : a o b
! // NOT, Negación, a = true : !a = false

### LOGICOS A NIVEL DE BITS
<< // Desplazamiento a la izquierda  a << b

**>>** // Desplazamiento a la derecha  a >> b

**>>>** // Desplazamiento a la derecha sin signo  a >>> b

& // AND  a & b

^ // XOR  a ^ b

| // OR  a | b

~ // NOT  a | b```


## addEventListener:
Este metodo sirve para escuchar cualquier tipo de evento que ocurra dentro de un objeto, estos objetos pueden ser un elemento HTML, una ventana, el mismo documento, un XMLhttpRequest.

Los eventos pueden ser:

blur: Cuando el elemento pierde el foco.

click: El usuario hace clic sobre el elemento.

dblclick: El usuario hace doble clic sobre el elemento.

focus: El elemento gana el foco.

keydown: El usuario presiona una tecla.

keypress: El usuario presiona una tecla y la mantiene pulsada.

keyup: El usuario libera la tecla.

load: El documento termina su carga.

mousedown: El usuario presiona el botón del ratón en un elemento.

mousemove: El usuario mueve el puntero del ratón sobre un elemento.

mouseout: El usuario mueve el puntero fuera de un elemento.

mouseover: El usuario mantiene el puntero sobre un elemento.

mouseup: El usuario libera el botón pulsado del ratón sobre un elemento.

unload: El documento se descarga, bien porque se cierra la ventana, bien porque se navega a otra página.

Syntaxis
