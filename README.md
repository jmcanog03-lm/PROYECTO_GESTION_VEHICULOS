# PROYECTO_GESTION_VEHICULOS
Proyecto de una aplicacion que sirve para gestionar vehículos junto a su conductor su ruta sus sensores y su mercancia


## Qué es Git Flow

*Git flow es un modelo de ramificación para Git que ofrece un enfoque estructurado para el desarrollo de software. Define ramas específicas para diferentes propósitos y describe cómo deben interactuar. El objetivo es agilizar el proceso de desarrollo, gestionar los lanzamientos (releases) de manera eficaz y facilitar la colaboración entre los miembros del equipo.*

## Diagrama de FLujo de Este Repositorio para la realizacion del proyecto.

![Diagrama de Flujo Git Flow](img/diagraama.png)


## Ventajas de usar Git Flow

- **Separación clara de entornos**: la rama `main` contiene siempre código estable en producción, mientras que `develop` centraliza el desarrollo activo.
- **Desarrollo paralelo**: mediante ramas `feature`, varios miembros del equipo pueden trabajar simultáneamente sin interferencias.
- **Gestión controlada de versiones**: las ramas `release` permiten preparar versiones antes de su despliegue, asegurando calidad mediante pruebas.
- **Corrección rápida de errores críticos**: gracias a las ramas `hotfix`, se pueden solucionar fallos en producción de forma inmediata sin afectar al desarrollo en curso.
- **Mejora continua del código**: el uso de ramas específicas como `refactor` facilita la optimización del sistema sin introducir nuevas funcionalidades.

En un contexto donde la fiabilidad es clave (por ejemplo, garantizar que la mercancía se transporta en condiciones óptimas), este modelo ayuda a reducir errores, mejorar la trazabilidad de cambios y asegurar la estabilidad del sistema en todo momento.


## Extensiones que recomendamos usar en VS CODE

- **HTML**

![Diagrama de Flujo Git Flow](img/bootstrap.png)

![Diagrama de Flujo Git Flow](img/html.png)

*Estas extensiones para HTML y CSS las recomendamos porque nos va a facilitar mucho a la hora de declarar las variables como div se abren y se cierran solas.*

*Bootstrap la recomendamos porque nos permite declarar toda la estructura HTML y ademas permite hacer cosas como modales e importar iconos para nuestra web.*


- **GIT**

![Diagrama de Flujo Git Flow](img/git.png)

*Esta extension la recomendamos en relación a ver el grafico de flujo que va tomando nuetro proyecto en cuanto a ramas y si hay muchas burficificaciones o si hay algo que no cuadra en cuanto a combinar las ramas , nos sirve mucho para ver como avanza el proyecto.*


- **JAVA**

![Diagrama de Flujo Git Flow](img/java.png)

*Esto es lo necesario para empezar en Java y funciona junto al jdk de Java y contiene las siguientes cosas:*

 **🔹 1. Language Support for Java™ by Red Hat**

- *Autocompletado inteligente*
- *Navegación por el código*
- *Detección de errores*
- *Usa el servidor de lenguaje de Red Hat*

**🔹 2. Debugger for Java**

- *Permite ejecutar código paso a paso*
- *Breakpoints (puntos de parada)*
- *Inspección de variables*

**🔹 3. Test Runner for Java**

- *Ejecutar tests (JUnit)*
- *Ver resultados de pruebas*
- *Integración con testing*

**🔹 4. Maven for Java**

- *Gestión de dependencias*
- *Compilación del proyecto*
- *Soporte para proyectos Maven*

**🔹 5. Project Manager for Java**

- *Organiza proyectos Java*
- *Vista estructurada del proyecto*
- *Gestión de múltiples proyectos*


## Diagrama de Secuencia

![Diagrama de Flujo Git Flow](img/0.png)

**1. Trazabilidad de la Responsabilidad (Accountability)**

En un entorno de mercancías críticas, la **responsabilidad verificable** es el activo intangible más valioso.

* **Justificación:** La inclusión obligatoria del caso de uso `Iniciar Sesión` en las acciones del **Conductor** y el **Administrador** garantiza que cada interacción quede vinculada a una identidad única.

* **Valor:** Esto proporciona seguridad jurídica y transparencia, permitiendo reconstruir la cadena de custodia ante cualquier incidencia o auditoría externa.

 **2. Conciencia Situacional y Resiliencia**

El sistema transita de una logística reactiva a una **logística predictiva** mediante la integración del actor **Sensores**.
* **Justificación:** Los casos de uso `Enviar Datos GPS` y `Detectar Fallos` operan de forma autónoma a la intervención humana.

* **Valor:** Este flujo constante genera el intangible de **paz mental operativa**. La plataforma permite anticiparse a la pérdida de cadena de frío o desviaciones de ruta, protegiendo la reputación de la empresa y la integridad del producto antes de que el daño sea irreversible.

**3. Armonización de la Inteligencia Operativa**

El diseño justifica la convergencia de tres perspectivas distintas en una sola fuente de verdad:

1. **El Administrador:** Supervisión estratégica y gestión de talento.
2. **El Conductor:** Ejecución táctica y navegación.
3. **El Sistema de Sensores:** Verdad técnica objetiva (Temperatura, GPS, Estado).