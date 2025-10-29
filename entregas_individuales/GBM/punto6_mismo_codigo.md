# Punto 6: Generación de ejecutables con diferentes IDEs a partir del mismo código fuente

## IDEs utilizados
- **IDE 1:** **Visual Studio Code (VSC)** – Entorno de desarrollo libre - Versión 1.105
- **IDE 2:** **IntelliJ IDEA (JetBrains)** – Entorno de desarrollo propietario - Versión 2025.2.4

## Descripción de la tarea
Programa "cuenta atrás" en Python que cuenta de 10 a 0 y luego imprime "¡Despegue!"

## Código implementado

```python
# Código Python del programa cuenta atrás
for i in range(1, 11):
    print(i)

print("Despegue!")
```

## Respuestas a preguntas evaluativas

### Pregunta 1: ¿Qué diferencias encontraste al ejecutar el mismo código fuente en diferentes IDEs?
En **Visual Studio Code**, la ejecución del script es inmediata usando la terminal integrada o el botón de ejecución del intérprete Python antes habiendo instalado los plugins para su interpretacion.
En **IntelliJ IDEA**, fue necesario configurar un “Run Configuration” específico para Python, pero ofrece una depuración más potente y un entorno más estructurado. Sin embargo, es necesario instalar
plugins para poder ejecutarlo, seleccionar interprete etc.. si hubiesemos usado JetBrains PyCharms esto seria de forma automatica, tan facil como ejecutar Java o Kotlin en JetBrains IntelliJ IDEA.

### Pregunta 2: ¿Cuál de los IDEs te pareció más cómodo o eficiente para ejecutar el código Python o el lenguaje que hayas elegido? ¿Por qué?
Vamos a recapitular, para proyectos simples o scripts, **Visual Studio Code** es más cómodo y rápido gracias a su ligereza y flexibilidad. Sin embargo, para proyectos grandes o con múltiples dependencias,
**IntelliJ IDEA** es más eficiente por su integración avanzada, refactorización automática y potente depurador. Podemos decir, que esta es la gran diferencia de ambos. Viendo esta perspectiva creo que
seria mas optimo usar VSC para ejecutar este simple codigo de Python.


## Evidencias
![Captura de pantalla 2025-10-26 182202.png](capturas%2FCaptura%20de%20pantalla%202025-10-26%20182202.png)
![Captura de pantalla 2025-10-26 182912.png](capturas%2FCaptura%20de%20pantalla%202025-10-26%20182912.png)

## Observaciones
[Comentarios adicionales]