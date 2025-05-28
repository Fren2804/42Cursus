# 🔧🧱 In Progress 🧱🔧
# 🏢Cursus 42 - Campus 42 Madrid 🇪🇸

Bienvenido a mi repositorio del **Cursus 42**, donde iré subiendo todos mis proyectos completados y corregidos. Aquí encontrarás implementaciones en C, estructuras de datos, algoritmos y otros ejercicios desarrollados en el marco del programa de formación de **42 Madrid**. Dentro de cada repositorio habrá mas información en detalle de cada proyecto.

---
## Índice

1. [Libft](https://github.com/Fren2804/Libft)🏠  
   1.1 [Explicación](#explicación-libft)
2. [Get_Next_Line](https://github.com/Fren2804/Get_Next_Line)🏠  
   2.1 [Explicación](#explicación-get_next_line)
3. [Ft_Printf](https://github.com/Fren2804/Ft_Printf)🏠  
   3.1 [Explicación](#explicación-ft_printf)
4. Born2beroot🏠  
   4.1 [Explicación](#explicación-born2beroot)
5. [Fdf](https://github.com/Fren2804/FDF)🏠  
   5.1 [Explicación](#explicación-fdf)
6. [Pipex](https://github.com/Fren2804/Pipex)🏠  
   6.1 [Explicación](#explicación-pipex)
7. [Push_Swap](https://github.com/Fren2804/Push_Swap)🏠  
   7.1 [Explicación](#explicación-push_swap)
8. Exam02🏠  
   8.1 [Explicación](#explicación-exam02)



# Explicación

## Explicación Libft

Este es el primer proyecto del campus 42, en el que se nos introducen ciertas pautas fundamentales y se nos pide replicar muchas de las funciones básicas de la biblioteca estándar de C. El objetivo principal es que comprendamos en profundidad cómo funcionan estas funciones, su propósito y cómo implementarlas correctamente, ya que formarán la base para los próximos proyectos.

Durante este proyecto, aprendemos a crear un Makefile que automatiza la compilación y generación de la biblioteca. También nos enfocamos en vincular todos los archivos .c mediante un archivo de cabecera .h, lo que nos permite generar una biblioteca completamente funcional.

La experiencia adquirida en este proyecto nos ayuda a dominar el manejo de memoria dinámica, las cadenas de caracteres y otras operaciones fundamentales en C, sentando las bases para convertirnos en desarrolladores más sólidos y organizados.

## Resultado Libft

![Libft Results](https://github.com/user-attachments/assets/11105315-a2a0-4cc2-8c29-3cc0c523f2e4)

## Repositorio Libft

https://github.com/Fren2804/Libft

## Explicación Get_Next_Line

Este fue mi segundo proyecto, en el que se nos pide implementar una función capaz de leer línea por línea desde un descriptor de archivo (fd) hasta alcanzar el final del mismo. El objetivo es crear una función que devuelva cada línea de texto, respetando los saltos de línea y sin perder información.

En este proyecto solo se permiten dos archivos .c y un archivo de cabecera .h, y no es necesario crear un Makefile, ya que se centra únicamente en la lógica de lectura.

El reto consiste en gestionar correctamente los buffers de lectura, almacenar la información leída y manejar posibles errores o finales de archivo. Es un excelente ejercicio para entender la gestión de la memoria dinámica, el control de lectura de archivos y cómo manipular cadenas en C.

## Resultado Get_Next_Line

![GNL Results](https://github.com/user-attachments/assets/1ad5421b-b87a-4e28-9747-80757af13d87)

## Repositorio Get_Next_Line

https://github.com/Fren2804/Get_next_line

## Explicación Ft_Printf

En este proyecto teníamos que recrear la función printf, pero también se requería que la implementáramos como parte de una biblioteca, lo que nos devolvía a la creación de un Makefile para gestionar la compilación y vinculación de los archivos.

Uno de los principales desafíos de este proyecto fue aprender a trabajar con argumentos variádicos en C, usando las macros de la biblioteca <stdarg.h> para gestionar múltiples argumentos de manera flexible. Además, nos centramos en cómo interpretar y formatear los datos de salida según las especificaciones de formato (como %d, %s, %p, etc.), así como en imprimirlos correctamente en la salida estándar.

Este proyecto no solo nos permitió afianzar conceptos previos sobre cadenas y buffers, sino también adquirir habilidades avanzadas en el formateo y la gestión eficiente de datos. Fue una gran oportunidad para profundizar en la funcionalidad interna de una de las funciones más utilizadas en C.

## Resultado Ft_Printf

![Printf Results](https://github.com/user-attachments/assets/6b7c017b-050f-4d59-adc0-a8d8bd9bd45f)

## Repositorio Ft_Printf

https://github.com/Fren2804/Ft_printf

## Explicación Born2beroot

En este proyecto aprendemos a administrar y configurar un sistema operativo Linux desde cero, reforzando los fundamentos de la administración de sistemas. El objetivo es entender cómo instalar y configurar un servidor de manera segura, eficiente y siguiendo las buenas prácticas.

Durante este proyecto, creamos una máquina virtual con Debian o Rocky con sus particiones y configuramos los usuarios, los grupos y los permisos adecuados para asegurar el sistema. También nos adentramos en la configuración de servicios esenciales, como el SSH, y en cómo aplicar políticas de seguridad con herramientas como ufw (cortafuegos) y sudo, para conceder permisos de administración de forma controlada.

Uno de los aspectos más importantes de este proyecto es la implementación de políticas de contraseñas y la creación de un sistema que cumpla con los estándares de seguridad, lo que nos da una base sólida para la administración de servidores y nos prepara para entornos de producción reales.

## Resultado Born2beroot

## Explicación Fdf

El proyecto FDF ya pertenece al nuevo círculo, donde se nos permite y se espera que utilicemos nuestra biblioteca libft, así como las funciones get_next_line y ft_printf que implementamos en proyectos anteriores. Además, este proyecto nos introduce a una nueva herramienta: la MiniLibX, una biblioteca gráfica sencilla diseñada para renderizar gráficos en 2D y 3D.

El objetivo principal de este proyecto es leer un archivo que contiene un mapa con altitudes (y opcionalmente colores) y representarlo de forma gráfica en un entorno 3D utilizando proyecciones isométricas. Para lograrlo, debemos procesar correctamente los datos del archivo, interpretar las coordenadas y pintar los puntos en la ventana gráfica de MiniLibX.

Este proyecto nos ayuda a profundizar en la manipulación de datos espaciales, las transformaciones geométricas y cómo renderizar elementos en una interfaz gráfica básica. Además, pone a prueba nuestras habilidades para integrar varias bibliotecas y reforzar conceptos clave de la programación estructurada.

## Resultado Fdf

![FDF Results](https://github.com/user-attachments/assets/5f6202fa-6891-4383-a12e-2b66a334d3f2)

## Repositorio Fdf

https://github.com/Fren2804/Fdf

## Explicación Pipex

El objetivo principal de este proyecto es comprender el funcionamiento de los procesos y la comunicación entre ellos, especialmente cómo la shell ejecuta los comandos y gestiona los errores. Nos adentramos en el uso de los pipes y las llamadas al sistema como fork, execve, dup2 y wait, fundamentales para la programación en C a nivel de sistema.

Durante este proyecto, debemos implementar un programa que simule el comportamiento de la shell cuando encadenamos comandos usando el operador | (pipe). Esto implica redirigir las entradas y salidas estándar, gestionar correctamente la duplicación de descriptores de archivo y asegurarnos de que los errores se manejen de forma clara y robusta.

Además, nos obliga a reforzar nuestra comprensión de la gestión de procesos en Unix/Linux y cómo los programas pueden comunicarse mediante pipes para trabajar en conjunto. Es un paso clave para desarrollar herramientas más complejas y aprender cómo funcionan los procesos en segundo plano y la ejecución de comandos en sistemas Unix.

## Resultado Pipex

![Pipex Results](https://github.com/user-attachments/assets/967b3616-dace-4b41-912f-2f36b2a709bc)

## Repositorio Pipex

https://github.com/Fren2804/Pipex

## Explicación Push_Swap

Este proyecto tiene como objetivo desarrollar un algoritmo eficiente para ordenar una pila de números utilizando un conjunto limitado de operaciones, simulando el comportamiento de un sistema de ordenación específico.

En Push_Swap trabajamos con dos pilas (A y B) y disponemos de un conjunto de instrucciones básicas (sa, sb, pa, pb, ra, rb, rra, rrb, rr, rrr) que nos permiten realizar operaciones de intercambio, rotación y transferencia entre las pilas. La clave del proyecto es encontrar el algoritmo más eficiente posible, minimizando la cantidad de movimientos necesarios para ordenar completamente la pila A.

Este proyecto nos obliga a pensar de manera lógica y estratégica, aplicando conceptos de algoritmos de ordenación y optimización. Además, refuerza nuestras habilidades en el manejo de estructuras de datos (pilas y listas enlazadas) y nos enseña la importancia de la eficiencia en la programación.

## Resultado Push_Swap

![Push Swap Results](https://github.com/user-attachments/assets/732e2423-e6b7-4930-be7f-2d1071cca999)


## Repositorio Push_Swap

https://github.com/Fren2804/Push_Swap

## Explicación Exam02

En este primer examen, nos enfrentamos a 4 ejercicios aleatorios de distintos niveles de dificultad, ordenados de menor a mayor. Cada uno de estos ejercicios pone a prueba conceptos clave de C y nuestra capacidad para escribir código eficiente y correcto bajo presión.

   Mis ejercicios fueron:

⚫ Ejercicio 1 - Rotone

En este ejercicio, se nos pide rotar cada carácter al siguiente en el alfabeto, de modo que 'a' se convierte en 'b' y 'Z' en 'A'.

⚫ Ejercicio 2 - Reverse bits

Aquí se trata de invertir los 8 bits de un número. Por ejemplo, el valor 0010 0110 debe transformarse en 0110 0010.

⚫ Ejercicio 3 - Atoi_base

Este fue el más desafiante para mí, ya que al principio no tuve en cuenta que la base podía contener letras mayúsculas y minúsculas simultáneamente (por ejemplo, 1aA es válido). Tuve que convertir una cadena en un número entero usando cualquier base que pasaran, lo que implica manejar la validación y conversión de caracteres de forma cuidadosa.

⚫ Ejercicio 4 - Itoa

Finalmente, el itoa consiste en convertir un número entero en una cadena de caracteres, respetando los signos y teniendo en cuenta el valor mínimo de los enteros (caso especial de INT_MIN en C).

## Resultado Exam02

![Exam02 Results](https://github.com/user-attachments/assets/b3579911-ac15-40bb-a538-f8d93efe81d5)

