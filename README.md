# Trabajo Práctico Integrador  2026
## Introducción al análisis de datos con Python y GitHub

Este práctico está pensado como una primera experiencia de análisis de datos.  
No vamos a importar archivos externos. Los datos estarán cargados directamente en el código.

La idea es trabajar con datos de estudiantes y responder preguntas simples usando Python, pandas y gráficos.

## Objetivo del trabajo

Desarrollar un pequeño análisis de datos educativos que permita observar:
- cantidad de estudiantes;
- promedio de edad;
- promedio de notas;
- estudiantes aprobados y desaprobados;
- relación entre trabajo y rendimiento;
- uso de IA;
- horas de estudio y nota final.
Al final, el trabajo debe subirse a GitHub.

## Datos del trabajo
Vamos a usar una lista de diccionarios. Pueden utilizar la que se presenta a continuación o crear una propia.
Cada diccionario representa a un estudiante.

estudiantes = [
    {"nombre": "Ana", "edad": 22, "trabaja": "Sí", "horas_estudio": 5, "nota": 8, "usa_ia": "Sí"},
    {"nombre": "Juan", "edad": 28, "trabaja": "Sí", "horas_estudio": 2, "nota": 5, "usa_ia": "No"},
    {"nombre": "Sofía", "edad": 20, "trabaja": "No", "horas_estudio": 6, "nota": 9, "usa_ia": "Sí"},
    {"nombre": "Pedro", "edad": 24, "trabaja": "No", "horas_estudio": 3, "nota": 6, "usa_ia": "No"},
    {"nombre": "Lucía", "edad": 31, "trabaja": "Sí", "horas_estudio": 4, "nota": 7, "usa_ia": "Sí"},
    {"nombre": "Martín", "edad": 19, "trabaja": "No", "horas_estudio": 2, "nota": 4, "usa_ia": "No"},
    {"nombre": "Carla", "edad": 26, "trabaja": "Sí", "horas_estudio": 7, "nota": 9, "usa_ia": "Sí"},
    {"nombre": "Diego", "edad": 23, "trabaja": "No", "horas_estudio": 4, "nota": 7, "usa_ia": "Sí"},
]

## Actividad 1: convertir los datos en una tabla

1.   Elemento de la lista
2.   Elemento de la lista
Importá pandas y convertí la lista `estudiantes` en un DataFrame llamado `df`.
Luego mostrá la tabla.

## Actividad 2: calcular indicadores generales

Calculá y mostrá:
1. cantidad total de estudiantes;
2. promedio de edad;
3. promedio de nota;
4. promedio de horas de estudio.

## Actividad 3: aprobados y desaprobados

Consideramos aprobado a quien tiene nota igual o mayor a 6.
Creá una nueva columna llamada `estado`, con los valores:
- `Aprobado`
- `Desaprobado`
Luego contá cuántos estudiantes aprobaron y cuántos desaprobaron.

## Actividad 4: trabajo y rendimiento

Separá los estudiantes en dos grupos:
- quienes trabajan;
- quienes no trabajan.
Luego calculá el promedio de nota de cada grupo.

## Actividad 5: uso de IA

Contá:
- cuántos estudiantes usan IA;
- cuántos estudiantes no usan IA.

## Actividad 6: nota más alta y nota más baja

Mostrá:
- el nombre del estudiante con la nota más alta;
- el nombre del estudiante con la nota más baja.

## Actividad 7: gráficos
Realizá al menos dos gráficos:
- gráfico de barras con las notas de cada estudiante;
- gráfico de dispersión con horas de estudio y nota final.
Podés usar matplotlib.

## Actividad 8: conclusiones

Escribí una conclusión breve respondiendo:
1. ¿Cuál fue el promedio general de notas?
2. ¿La mayoría aprobó o desaprobó?
3. ¿Hay diferencias entre quienes trabajan y quienes no trabajan?
4. ¿Qué información puede servirle a una institución educativa?

# Entrega en GitHub

El trabajo debe subirse a un repositorio de GitHub.
El repositorio debe incluir:
- este notebook;
- un archivo `README.md`;
- al menos 3 commits.

Ejemplos de commits:
1. `Agrega datos de estudiantes`
2. `Calcula indicadores principales`
3. `Agrega gráficos y conclusiones`
El enlace del repositorio será la entrega final.
