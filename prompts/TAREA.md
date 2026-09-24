# Tarea: Mi prompt profesional
## Funcionalidad elegida
Se eligió como funcionalidad un **módulo sencillo de cálculo de notas** para un curso académico. Este sistema debe permitir ingresar las notas de prácticas y exámenes calcular el promedio final y determinar si el estudiante aprobó o desaprobó.
 
## Version 1: prompt basico
Calcula el promedio de notas de un alumno.
 
## Version 2
Actúa como un programador backend. Escribe un script en Python para calcular el promedio de notas de un estudiante que tiene 3 prácticas 20% cada una y 1 examen final 40%.
 
## Version 3: prompt final
 Rol: Eres un ingeniero de software senior experto en Python.
Instrucción: Diseña una función en Python llamada calcular_promedio que reciba una lista de 3 notas de prácticas y 1 nota de examen final, calcule el promedio ponderado prácticas: 20%, examen fina 40% y retorne    el promedio final y el estado Aprobado si es  13, Desaprobado en caso contrario.
Contexto: El sistema se utilizará en una institución educativa para automatizar la libreta de notas de los estudiantes de primer ciclo.
Ejemplos:
- Entrada: practicas = [14, 15, 13], examen_final = 16
- Salida esperada: promedio: 14.6, estado: Aprobado
Formato: Devuelve únicamente el bloque de código Python documentado, seguido de una tabla Markdown que explique brevemente cómo se usaron los componentes.
Restricciones: No utilices librerías externas ni frameworks solo Python. Valida que las notas estén en el rango de 0 a 20.
## Componentes del prompt final
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Actua como ingeniero senior de Python. |
| Instruccion | Diseñar la funcion calculo_promedio y calculo de estado|
| Contexto | Uso en una institución educativa para automatizar libretas de notas de primer ciclo.|
| Ejemplo |Entrada con lista de prácticas (14, 15, 13) y examen 16 con su salida esperada en diccionario. |
| Formato |Bloque de código Python documentado seguido de una tabla Markdown explicativa. |

## Evaluacion del resultado
 | Que revisar | Cumple (Si/No) |
|------------|--------------------|
| ¿El codigo usa solamente Python? | Si|
| ¿Se aplicaron los porcentajes que se dijeron de 20 y 40? | Si|
| ¿Valida que las notas estan en un rango de 0-20?| Si|
| ¿La salida da exactamente lo que se requrio en cadricula? | Si|
## Errores que evite
 En la Versión 1 el prompt era tan abierto que la IA asumió ponderaciones al azar. Lo evité estructurando claramente los pesos de las notas.

 En lugar de dejar que la IA inventara la escala de notas o el criterio de aprobación, especifiqué explícitamente que la nota aprobatoria mínima es 13 y el rango válido es de 0 a 20.
