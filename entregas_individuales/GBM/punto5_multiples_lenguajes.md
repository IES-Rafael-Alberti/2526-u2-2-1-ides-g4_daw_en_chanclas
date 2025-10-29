# Punto 5: Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE

## IDE utilizado
- **IDE:** **IntelliJ IDEA (JetBrains)** – Entorno de desarrollo propietario - Versión 2025.2.4

## Descripción de la tarea
Programa "cuenta atrás" que cuenta de 10 a 0 y luego imprime "¡Despegue!"

### Lenguajes utilizados
- **Lenguaje 1:** Java
- **Lenguaje 2:** Python

## Código implementado

### Lenguaje 1: Java
```Java
public class Main {
    public static void main(String[] args) {
        for (int i = 1; i <= 10; i++) {
            System.out.println(i);
        }
        System.out.println("Despegue!");
        System.out.println();
    }
}
```

### Lenguaje 2: Python
```Python
for i in range(1, 11):
    print(i)

print("Despegue!")
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?
En IntelliJ IDEA, se crearon dos proyectos: uno en Java y otro en Kotlin. El proceso de compilación y ejecución fue similar, ya que el IDE detecta automáticamente el lenguaje y configura las
dependencias necesarias porque IntelliJ una de sus especialidades es justamente estos 2 lenguajes.

### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?
- En **Java**, el ejecutable se genera como un archivo `.class` dentro de la carpeta `out/production`.
- En **Kotlin**, el compilador también genera bytecode Java, pero los archivos resultantes se ubican en una estructura de carpetas ligeramente diferente.  
  Ambos se ejecutan sobre la Java Virtual Machine (JVM), ya lo hemos visto en el anterior tema, pero Kotlin requiere menos líneas de código para lograr el mismo resultado,
  que supongo que lo veremos en un futuro proximo.

## Evidencias
![Captura de pantalla 2025-10-26 182132.png](capturas%2FCaptura%20de%20pantalla%202025-10-26%20182132.png)
![Captura de pantalla 2025-10-26 182202.png](capturas%2FCaptura%20de%20pantalla%202025-10-26%20182202.png)

## Observaciones
[Comentarios adicionales]
