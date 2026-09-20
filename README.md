# Cálculo del promedio de tres notas

## Descripción

Este proyecto consiste en un programa desarrollado en Python que permite calcular el promedio de tres notas mediante el uso de una función con parámetros y retorno de valores.

## Objetivo

Aplicar el uso de funciones con parámetros y retorno de valores para resolver un problema sencillo de la vida real.

## Funcionamiento

El programa utiliza una función llamada `calcular_promedio`, que recibe tres parámetros: `nota1`, `nota2` y `nota3`.

La función suma las tres notas, divide el resultado para tres y utiliza `return` para devolver el promedio calculado.

Después, se realiza una llamada a la función y el resultado se muestra en pantalla.

## Código de ejemplo

```python
def calcular_promedio(nota1, nota2, nota3):
    promedio = (nota1 + nota2 + nota3) / 3
    return promedio


nota1 = 8.5
nota2 = 9.0
nota3 = 7.5

resultado = calcular_promedio(nota1, nota2, nota3)

print("Nota 1:", nota1)
print("Nota 2:", nota2)
print("Nota 3:", nota3)
print("Promedio final:", resultado)
```

## Requisitos utilizados

* Una función.
* Parámetros de entrada.
* Uso de `return`.
* Llamada a la función.
* Mostrar el resultado en pantalla.

## Resultado esperado

```text
Nota 1: 8.5
Nota 2: 9.0
Nota 3: 7.5
Promedio final: 8.333333333333334
```

## Lenguaje utilizado

**Python**
