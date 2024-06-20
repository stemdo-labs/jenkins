### Ejercicio 1: Configuración de un Job Simple

Crea un trabajo en Jenkins que realice las siguientes tareas:
1. Clona un repositorio de GitHub.
2. Ejecuta un script de shell que compile un proyecto Java utilizando Maven.
3. Guarda los artefactos generados en Jenkins.
4. Configura el trabajo para que se ejecute automáticamente cada hora.


### Ejercicio 2: Pipeline Declarativo con Stages

Crea un Pipeline en Jenkins utilizando la sintaxis declarativa que realice las siguientes etapas:
1. **Build:** Compila un proyecto Node.js.
2. **Test:** Ejecuta los tests unitarios.
3. **Deploy:** Despliega la aplicación en un servidor de prueba si los tests son exitosos.


### Ejercicio 3: Integración Continua con Notificaciones

Configura un trabajo en Jenkins que realice integración continua para un proyecto Python. El trabajo debe:
1. Clonar el repositorio de GitHub.
2. Instalar las dependencias del proyecto utilizando `pip`.
3. Ejecutar los tests unitarios.
4. Notificar el resultado de la compilación (éxito o fallo) a través de correo electrónico.


### Ejercicio 4: Implementación de un Multibranch Pipeline

Configura un Multibranch Pipeline en Jenkins para un proyecto alojado en un repositorio Git. El pipeline debe detectar automáticamente todas las ramas del repositorio y ejecutar el siguiente pipeline:
1. Compilar el proyecto.
2. Ejecutar los tests.
3. Generar un informe de cobertura de código.


### Ejercicio 5: Implementación de un Job de Despliegue con Parámetros

Crea un trabajo en Jenkins que despliegue una aplicación web en diferentes entornos (desarrollo, prueba, producción). El trabajo debe:
1. Solicitar al usuario que seleccione el entorno de despliegue (por ejemplo, a través de parámetros de entrada).
2. Desplegar la aplicación en el entorno seleccionado utilizando un script de shell.
