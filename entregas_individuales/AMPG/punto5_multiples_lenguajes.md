# Punto 2.5: Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE

## IDE utilizado
- **IDE elegido:** Visual Studio Code (propietario)

## Descripción de la tarea
He escrito un programa que cuenta de 10 a 0 y luego imprime “¡Despegue!”. Implementé la solución en dos lenguajes distintos (por ejemplo, Python y Java) usando Visual Studio Code, y comprobé tanto el proceso de generación como de ejecución en ambos casos.

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?
En Visual Studio Code, instalé las extensiones necesarias para cada lenguaje (por ejemplo, Python y Java). 
- Escribí el programa en ambos lenguajes en archivos separados dentro del mismo espacio de trabajo.
- Para **Python**, simplemente ejecuté el archivo usando la extensión de Python o usando la opción de “Run” que aparece sobre el código.
- Para **Java**, utilicé la extensión “Extension Pack for Java” para compilar y ejecutar el archivo. El IDE automáticamente compiló el código fuente antes de ejecutar.

Ambos procesos se manejan fácilmente desde la barra lateral y la terminal integrada, lo que permite alternar entre lenguajes con solo cambiar de archivo y extensión.

### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?
- En **Python**, la ejecución es directa e inmediata; no requiere compilación. Basta con pulsar “Run” y el intérprete muestra el resultado en la terminal integrada.
- En **Java**, antes de ejecutar el programa es necesario compilarlo para generar el archivo .class. Luego, el IDE lanza ese ejecutable desde la terminal integrada.

La principal diferencia es que en Python basta con guardar y ejecutar, mientras que en Java hay que compilar primero y luego ejecutar, lo que implica un paso extra en el flujo de trabajo.

## Evidencias
![Captura 1](capturas/punto5_captura1.png)
![Captura 2](capturas/punto5_captura2.png)
