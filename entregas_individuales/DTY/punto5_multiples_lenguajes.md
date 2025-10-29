# Punto 5: Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE

## IDE utilizado
- **IDE:** [Fleet]

## Descripción de la tarea
Programa "cuenta atrás" que cuenta de 10 a 0 y luego imprime "¡Despegue!"

### Lenguajes utilizados
- **Lenguaje 1:** [Java]
- **Lenguaje 2:** [Kotlin]

## Código implementado

### Lenguaje 1: [Java]
```[lenguaje]
public class main {
    public static void main(String[] args) {
        for (int i = 10; i >= 0; i--) {
            System.out.println(i);
        }
        System.out.println("¡Despegue!");
    }
}
```

### Lenguaje 2: [Kotlin]
```[lenguaje]
fun main() {
    for (i in 10 downTo 0) {
        println(i)
    }
    println("¡Despegue!")
}
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?
- Dandole al boton de ejecutar, usando el atajo de teclado dentro del IDE o bien haciendo uso del comando correspondiente desde la terminal.
### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?
- Para java en la terminal poner javac nombre_del_archivo
- Para kotlin hay que configurar el gradle del proyecto
## Evidencias
![Ejecución en lenguaje 1](capturas/punto5_lenguaje1_ejecucion.png)
![Ejecución en lenguaje 2](capturas/punto5_lenguaje2_ejecucion.png)
