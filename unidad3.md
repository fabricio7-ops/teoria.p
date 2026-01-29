<p align="center">📘 Portafolio – Modularidad y Uso de Arreglos</p>
<p align="center">📌 1. Modularidad</p>

La modularidad es un enfoque de diseño en programación que consiste en separar un programa en partes más pequeñas llamadas módulos o funciones, donde cada una cumple una tarea específica dentro del sistema.

Ventajas

🔹 Reutilización: Un mismo módulo puede emplearse en diferentes programas sin necesidad de reescribirlo.

🔹 Mantenimiento: Permite identificar y corregir errores de manera más rápida y sencilla.

🔹 Legibilidad: El código resulta más claro y comprensible al estar dividido en secciones.

🔹 Trabajo colaborativo: Facilita que varios programadores desarrollen distintas partes del programa al mismo tiempo.

Paso por valor

En este método, la función recibe una copia del valor de la variable.
Cualquier cambio realizado dentro de la función no modifica el valor original.

Ejemplo

La función recibe una copia del valor de la variable x.

Dentro de la función, esa copia se altera (x = 25).

Sin embargo, el valor original (numero = 5) permanece igual, ya que solo se trabajó con una copia.

Es similar a prestar una fotocopia de un cuaderno: puedes escribir sobre ella sin afectar el cuaderno original.

Imagen 1

<p align="center"><img width="615" height="398" src="https://github.com/user-attachments/assets/b2190255-b261-464c-a27b-e389210585a1" /></p>
Resultado

Imagen 2

<p align="center"><img width="443" height="81" src="https://github.com/user-attachments/assets/01f0752a-5bba-4244-9294-722fba3e7c4a" /></p>
Paso por referencia

En este caso, la función recibe la dirección de memoria de la variable.
Por lo tanto, cualquier modificación realizada sí afecta al valor original.

Ejemplo

La función recibe la dirección de memoria de la variable (&numero).

Dentro de la función se accede directamente al valor original y se modifica (numero = 25).

El cambio se refleja fuera de la función, ya que se trabaja directamente con la variable original.

Es como prestar el cuaderno original: cualquier marca hecha quedará registrada.

Imagen 3

<p align="center"><img width="771" height="408" src="https://github.com/user-attachments/assets/e0d3c495-6c38-4ba2-a4ea-a330f3d5a046" /></p>
Resultado

Imagen 4

<p align="center"><img width="812" height="128" src="https://github.com/user-attachments/assets/40af1dd8-0ba7-47a6-9500-22c285c36763" /></p>
<p align="center">📌 Arreglos</p>

Un arreglo es una estructura de datos que permite almacenar múltiples valores del mismo tipo en ubicaciones contiguas de memoria.

Características

🔹 Todos los elementos almacenados son del mismo tipo de dato.

🔹 Cada elemento se identifica mediante un índice o posición.

🔹 En la mayoría de lenguajes, los índices comienzan desde 0.

Ventajas

🔹 Facilitan la organización de datos similares.

🔹 Permiten acceder rápidamente a cualquier elemento.

🔹 Son ideales para trabajar con ciclos repetitivos como for o while.

<p align="center">Tipos de Arreglos</p>
1. Arreglo unidimensional

Consiste en una lista simple de elementos dispuestos en una sola dimensión.

Ejemplo

El arreglo numeros contiene cinco valores enteros y cada uno se accede mediante un índice.

Imagen 5

<p align="center"><img width="733" height="343" src="https://github.com/user-attachments/assets/2d7639bf-0013-4a50-a995-d537e6e0dd70" /></p>
Resultado

Imagen 6

<p align="center"><img width="761" height="255" src="https://github.com/user-attachments/assets/8715174e-0461-4a78-ab31-e8e7ace5db01" /></p>
2. Arreglo bidimensional (matriz)

Se representa como una tabla formada por filas y columnas.

Ejemplo

La matriz tiene 2 filas y 3 columnas, y se accede usando dos índices.

Imagen 7

<p align="center"><img width="827" height="474" src="https://github.com/user-attachments/assets/029312fc-c7d7-4d93-829a-809a5710fa03" /></p>
Resultado

Imagen 8

<p align="center"><img width="828" height="177" src="https://github.com/user-attachments/assets/86795f88-3e4e-4032-a050-3a63bae7232c" /></p>
3. Arreglo multidimensional

Son arreglos con más de dos dimensiones, utilizados para representar estructuras de datos más complejas.

Ejemplo

El arreglo cubo es tridimensional y se accede mediante tres índices.

Imagen 9

<p align="center"><img width="837" height="439" src="https://github.com/user-attachments/assets/d18384f5-270a-4cd3-9939-bdcc62399b84" /></p>
Resultado

Imagen 10

<p align="center"><img width="795" height="275" src="https://github.com/user-attachments/assets/852c69d6-d2c4-4447-a0f4-b65eb132abc2" /></p>
<p align="center">Principales dificultades en la aplicación de los contenidos</p>

Comprender la abstracción de la modularidad y el uso de funciones.

Distinguir correctamente entre paso por valor y paso por referencia.

Visualizar cómo se almacenan los arreglos en memoria.

Olvidar inicializar variables o arreglos.

Errores al acceder a índices fuera del rango permitido.

Uso incorrecto de punteros.

Dificultad para dividir problemas grandes en módulos pequeños.

Elegir incorrectamente qué datos pasar por valor o por referencia.

<p align="center">Reflexión crítica sobre los aprendizajes</p>

Durante esta unidad entendí la importancia de dividir los programas en módulos para lograr un código más ordenado y fácil de mantener. Aprendí a diferenciar claramente entre el paso de parámetros por valor y por referencia, comprendiendo su impacto en la modificación de datos. Asimismo, reforcé el uso de arreglos, desde los más simples hasta los multidimensionales, reconociendo que estos últimos requieren mayor práctica.

Aunque enfrenté dificultades conceptuales y errores de sintaxis, comprendí que la práctica constante y el apoyo en la documentación son fundamentales para mejorar. En general, esta unidad fortaleció mi razonamiento lógico y mi forma de estructurar soluciones en programación.

 ## <p align="center"> ■ Tareas  </p>

### ✔️ APE

Construcción de funciones y procedimientos en un lenguaje de programación

APE 1(https://docs.google.com/document/d/1C3Q6_FOu39zW4IpaChXCWc8oAnL87Hxh/edit)

### ✔️ AA

Curso virtual de Cisco Networking Academy (Nov 05, 2025 - Jan 05, 2026) 



<p align="center">📌 Conclusiones </p>

La modularidad permite desarrollar programas más organizados, claros y reutilizables, facilitando su mantenimiento.
El uso adecuado del paso por valor y por referencia es esencial para controlar la modificación de datos dentro de las funciones.
Los arreglos son estructuras clave para manejar grandes cantidades de información, aunque su correcta implementación requiere práctica.
En conjunto, estos contenidos contribuyen al desarrollo de un pensamiento lógico y estructurado, fundamental para resolver problemas más avanzados en programación. 

