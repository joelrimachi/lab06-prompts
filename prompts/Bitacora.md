# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (escribe aqui cual usaste)
 
## Ejercicio 2: Tokens y ventana de contexto
 
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. |34| 7|
| The students program in Java. |29|6|
| desafortunadamente |18 | 4|

La IA no muestra un resultado optimo ya que no tiene la estructura o informacion necesaria para dar respuesta a las indicaciones o preguntas que se le hace.
## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 |100% |BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5 |65.3% | LibroYa, LibroYa, BiblioTec, BiblioTec, LibroYa|
| 1 | 44.5%| BiblioTec, LibroYa, BiblioTec, LectoGo, BiblioTec|
| 1.8 | 32.2%|BiblioTec, BiblioTec, LibroYa, LibroYa, BiblioTec |

 
## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |Si |Si |
| Menciona a los usuarios principales |Si | Si|
| Tiene exactamente 3 funcionalidades | Si|No |
| Esta en 3 parrafos |No | Si|
| Lo usaria en un informe real |No| Si|

 
## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Actua como desarrollador Java |
| Instruccion | Crea un programa en Java usando una clase Producto con los atributos codigo, nombre, precio y stock. .|
| Contexto | para gestionar los productos de una tienda.|
| Ejemplo |Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato |Explica primero la estructura de la clase y luego presenta el codigo Java. |

 
## Ejercicio 6: Del prompt basico al profesional
| Que revisar | Cumple (Si/No) |
|------------|--------------------|
| ¿Está escrito en Java y usa Swing? | Si|
| ¿Pide correo y contraseña? | Si|
| ¿Explica el funcionamiento antes o después del código?| Si|
| ¿El código está organizado en clases? | Si|
| ¿Valida los datos que ingresa el usuario?| Si|

```text
Promt Profesional:
Actua como desarrollador Java. Crea un ejemplo
de login para una
aplicacion de escritorio utilizando Swing. El
usuario debe ingresar
correo y contrasena. Explica brevemente el
funcionamiento y presenta
el codigo organizado por clases. 

Promt Mejorado:
Mejora el codigo anterior con estas
restricciones: no uses librerias
externas, valida que el correo contenga @ y que
la contrasena tenga
al menos 8 caracteres, y muestra los mensajes
con JOptionPane. 
```
