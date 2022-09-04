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
