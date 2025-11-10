# 🔧🧱 In Progress 🧱🔧
# 🏢42 Cursus - Campus 42 Madrid 🇪🇸

Bienvenido a mi repositorio del **Cursus 42**. Aquí encontrarás implementaciones en C, estructuras de datos, algoritmos y otros ejercicios desarrollados en el marco del programa de formación de **42 Madrid**. Dentro de cada repositorio habrá mas información en detalle de cada proyecto.

---

## 📚 Índice de Proyectos

### 🔨 Proyectos Base

| Proyecto | Explicación | 📝 Descripción |
|----------|-------------|----------------|
| 🧱 [Libft](https://github.com/Fren2804/Libft) | [Explicación](#explicación-libft) | Implementación desde cero de funciones estándar de C. |
| 📄 [Get Next Line](https://github.com/Fren2804/Get_Next_Line) | [Explicación](#explicación-get_next_line) | Lectura línea por línea desde un descriptor de archivo. |
| 🖨️ [Ft_Printf](https://github.com/Fren2804/Ft_Printf) | [Explicación](#explicación-ft_printf) | Reimplementación de `printf` con flags, formatos y tipos. |
| 🧑‍💻 [Born2beroot](#explicación-born2beroot) | [Explicación](#explicación-born2beroot) | Configuración de servidores y administración en Linux. |

### 🧠 Proyectos Intermedios

| Proyecto | Explicación | 📝 Descripción |
|----------|-------------|----------------|
| 🗺️ [FDF](https://github.com/Fren2804/FDF) | [Explicación](#explicación-fdf) | Visualización 3D de mapas en wireframe usando MLX. |
| 🔗 [Pipex](https://github.com/Fren2804/Pipex) | [Explicación](#explicación-pipex) | Manejo de tuberías UNIX entre procesos. |
| 🔄 [Push Swap](https://github.com/Fren2804/Push_Swap) | [Explicación](#explicación-push_swap) | Algoritmo para ordenar con pila y operaciones limitadas. |
| 🐚 [Minishell](https://github.com/Fren2804/Minishell) | [Explicación](#explicación-minishell) | Shell personalizada que ejecuta comandos UNIX. |
| 🧊 [Cub3D](https://github.com/Fren2804/cub3D) | [Explicación](#explicación-cub3d) | Motor 3D estilo Wolfenstein con raycasting. |
| 🌐 [NetPractice](#explicación-netpractice) | [Explicación](#explicación-netpractice) | Simulaciones de redes y resolución de topologías IP. |
| 🍝 [Philosophers](https://github.com/Fren2804/Philosophers) | [Explicación](#explicación-philosophers) | Resolución del problema de los filósofos con hilos. |

### 🧠 Exámenes

| Proyecto | Explicación | 📝 Descripción |
|----------|-------------|----------------|
| 🧠 [Exam02](#explicación-exam02) | [Explicación](#explicación-exam02) | Pruebas de lógica, memoria y manejo de archivos en C. |
| 🧠 [Exam03](#explicación-exam03) | [Explicación](#explicación-exam03) | Evaluación avanzada de algoritmia y punteros. |
| 🧠 [Exam04](#explicación-exam04) | [Explicación](#explicación-exam04) | Examen con retos de programación de nivel intermedio. |
| 🧠 [Exam05](#explicación-exam04) | [Explicación](#explicación-exam05) | Evaluación práctica con retos de sistema. |
| 🧠 [Exam06](#explicación-exam04) | [Explicación](#explicación-exam06) | Nivel superior con problemas complejos de diseño. |

### 🔵 Módulos C++

| Proyecto | Explicación | 📝 Descripción |
|----------|-------------|----------------|
| 🔵 [CPP Module 0–4](https://github.com/Fren2804/CPP-Module-0-4) | [Explicación](#explicación-cpp-module-0-4) | Fundamentos de C++, clases, operadores y memoria. |
| 🟣 [CPP Module 5–9](https://github.com/Fren2804/CPP-Module-5-9) | [Explicación](#explicación-cpp-module-5-9) | C++ avanzado: herencia, templates, containers STL. |

### 🚀 Proyectos Finales

| Proyecto | Explicación | 📝 Descripción |
|----------|-------------|----------------|
| 🏗️ [Inception](https://github.com/Fren2804/Inception) | [Explicación](#explicación-inception) | Infraestructura de contenedores con Docker y servicios. |
| 💬 [IRC](https://github.com/Fren2804/Irc) | [Explicación](#explicación-irc) | Servidor IRC funcional bajo el protocolo RFC1459. |
| 🌌 [Transcendence](https://github.com/Fren2804/Transcendence) | [Explicación](#explicación-transcendence) | Proyecto web full-stack con NestJS, PostgreSQL y más. |


## 🧱 Explicación Libft

**Libft** es el primer proyecto del campus 42. Se trata de una reimplementación de muchas funciones estándar de la biblioteca de C.  
El objetivo principal es comprender en profundidad su funcionamiento, su utilidad y cómo implementarlas correctamente desde cero, ya que serán la base de muchos proyectos posteriores.

---

### 🧠 ¿Qué se aprende?

- Manejo de memoria dinámica en C.
- Manipulación de cadenas y arrays.
- Organización del código en archivos `.c` y `.h`.
- Creación de un Makefile para compilar una librería estática.
- Normas de estilo y buenas prácticas de programación.

Este proyecto nos enseña a **pensar como desarrolladores de bajo nivel**, prestando atención al detalle, la optimización y el diseño limpio del código.

---

### ✅ Resultado

![Libft Results](https://github.com/user-attachments/assets/11105315-a2a0-4cc2-8c29-3cc0c523f2e4)

---

### 📁 Repositorio

🔗 [https://github.com/Fren2804/Libft](https://github.com/Fren2804/Libft)

---


## 📄 Explicación Get_Next_Line

**Get Next Line** es el segundo proyecto del campus 42.  
Consiste en implementar una función capaz de leer un archivo línea por línea a través de un descriptor de archivo (`fd`), devolviendo cada línea sin perder los saltos de línea.

---

### 🧠 ¿Qué se aprende?

- Lectura fragmentada desde un descriptor de archivo.
- Gestión de buffers y almacenamiento temporal.
- Uso de memoria dinámica para construir cadenas de texto.
- Manipulación eficiente de punteros y strings en C.
- Manejo de condiciones de fin de archivo y errores.

En este proyecto solo se permiten **dos archivos `.c` y un `.h`**, y no se exige Makefile. Se trata de un desafío muy útil para entender cómo funciona la lectura por partes y cómo construir una lógica robusta de acumulación y entrega de datos.

---

### ✅ Resultado

![GNL Results](https://github.com/user-attachments/assets/1ad5421b-b87a-4e28-9747-80757af13d87)

---

### 📁 Repositorio

🔗 [https://github.com/Fren2804/Get_next_line](https://github.com/Fren2804/Get_next_line)

---


## 🖨️ Explicación Ft_Printf

**Ft_Printf** es el tercer proyecto del campus 42.  
En él, se nos pide **recrear la función `printf`**, pero implementándola como parte de una **librería**, lo que nos lleva nuevamente a crear un **Makefile** para gestionar la compilación y vinculación de los archivos.

---

### 🧠 ¿Qué se aprende?

- Uso de **argumentos variádicos** en C mediante `<stdarg.h>`.
- Interpretación y formateo de los distintos **especificadores de formato** (`%d`, `%s`, `%p`, `%x`, etc.).
- Conversión de datos a texto y su impresión en la salida estándar.
- Manejo de buffers, strings y funciones reutilizables.
- Organización modular del código y compilación de librerías.

Este proyecto refuerza la comprensión de las **funciones de salida y del formateo de datos**, permitiéndonos entender cómo trabaja internamente una de las funciones más emblemáticas del lenguaje C.

---

### ✅ Resultado

![Printf Results](https://github.com/user-attachments/assets/6b7c017b-050f-4d59-adc0-a8d8bd9bd45f)

---

### 📁 Repositorio

🔗 [https://github.com/Fren2804/Ft_printf](https://github.com/Fren2804/Ft_printf)

---


## 🧑‍💻 Explicación Born2beroot

**Born2beroot** es un proyecto orientado a introducirnos en la **administración de sistemas Linux** desde cero.  
El objetivo es aprender a instalar, configurar y asegurar un servidor siguiendo buenas prácticas del mundo real.

---

### 🧠 ¿Qué se aprende?

- Instalación de una **máquina virtual** con Debian o Rocky Linux.
- Creación y particionado manual del disco.
- Configuración de usuarios, grupos y permisos.
- Activación y securización del acceso **SSH**.
- Aplicación de **políticas de contraseñas** seguras.
- Configuración de herramientas clave como `sudo` y `ufw` (cortafuegos).

El proyecto hace hincapié en la **seguridad del sistema**, enseñando cómo protegerlo desde su instalación, y cómo establecer controles de acceso robustos para usuarios y administradores.

---

### ✅ Resultado

![Born2beroot Results](https://github.com/user-attachments/assets/01201ea8-6903-4b34-80fe-6bd01c795fe2)

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

## Explicación Philosophers

El objetivo principal de este proyecto es comprender el funcionamiento de los hilos (threads), la sincronización entre ellos y los problemas clásicos de concurrencia, como el de los filósofos comensales.

Durante este proyecto, debemos implementar una simulación del problema de los filósofos comensales, en el que varios filósofos se sientan alrededor de una mesa con un tenedor por cada filósofo. Y cada filósofo necesita dos tenedores para poder comer, lo que nos obliga a gestionar cuidadosamente el acceso concurrente a los recursos compartidos usando mutexes.

El proyecto se centra en aprender a evitar condiciones de carrera (race conditions), interbloqueos (deadlocks) y otros errores comunes en la programación concurrente. Esto se logra utilizando herramientas como pthread_create, pthread_mutex_lock, pthread_mutex_unlock, y otras funciones de la biblioteca pthread.

## Resultado Philosophers

<!-- ![Pipex Results](https://github.com/user-attachments/assets/967b3616-dace-4b41-912f-2f36b2a709bc) -->

## Repositorio Philosophers

https://github.com/Fren2804/Philosophers

## Explicación Minishell

El objetivo principal de este proyecto es implementar una versión simplificada de una shell de Unix (siguiendo el funcionamiento de como lo hace bash), permitiéndonos comprender cómo funciona internamente una shell real.

Durante este proyecto, debemos gestionar la lectura de comandos del usuario, su interpretación (parsing), la ejecución de comandos internos, los built-in (como cd, echo, export, etc.) y externos, el manejo de variables de entorno, la redirección de entrada/salida (<, >, >>), los heredoc (<<), los pipes (|), y la gestión de señales (como Ctrl+C, Ctrl+\ y Ctrl+D).

Esto implica un uso intensivo de llamadas al sistema como fork, execve, pipe, dup2, waitpid, así como estructuras de datos para organizar y ejecutar los comandos de forma correcta y robusta.

Minishell es un proyecto clave para profundizar en la programación de bajo nivel en C, entender cómo los procesos y la comunicación entre ellos funcionan, y reforzar la lógica detrás de la construcción de herramientas similares a las que usamos diariamente en la terminal.

## Resultado Minishell

<!-- ![Pipex Results](https://github.com/user-attachments/assets/967b3616-dace-4b41-912f-2f36b2a709bc) -->

## Repositorio Minishell

https://github.com/Fren2804/Minishell

