Proyecto: Agencia de Viajes

Este es un proyecto de aplicación móvil para Android desarrollado en una combinación de Kotlin y Java. La aplicación está orientada a la gestión o interfaz de una Agencia de Viajes.
📝 Descripción
La aplicación sirve como prototipo para una agencia de viajes. Actualmente, cuenta con una pantalla de bienvenida que permite el acceso a las funciones principales de la aplicación, como la navegación por menús y la gestión de procesos relacionados con viajes.
🏗️ Estructura del Proyecto
El proyecto sigue la estructura estándar de Android (Gradle) y utiliza una arquitectura basada en Activities.
Componentes Principales:
•
Paquete base: com.example.demo
•
Lenguajes: Kotlin (para la lógica principal y menús) y Java (para procesos específicos y pruebas).
•
Actividades:
◦
MainActivity.kt: Pantalla de inicio de la aplicación.
◦
activity_menu.kt: Menú principal del sistema.
◦
activity_proceso.java: Actividad destinada al manejo de flujos de trabajo o procesos internos.
◦
activity_prueba.java: Actividad utilizada para pruebas de componentes o lógica.
Recursos Visuales (Layouts):
•
activity_main.xml: Diseño de la pantalla de bienvenida con título, imagen de un bus y botón de acceso.
•
activity_menu.xml: Interfaz del menú principal.
•
activity_proceso.xml: Contenedor para la lógica de procesos.
•
activity_prueba.xml: Interfaz de experimentación.
🔄 Flujo de la Aplicación
1.
Inicio (MainActivity): Al abrir la app, el usuario es recibido con el título "AGENCIA DE VIAJES" y una imagen representativa.
2.
Acceso: El usuario interactúa con el botón de "Acceso" para ingresar al sistema principal.
3.
Navegación (Menu): Una vez autenticado o habiendo presionado acceder, se redirige a la pantalla de menú principal (activity_menu), desde donde se podrán gestionar las diferentes opciones de la agencia.
4.
Procesos: A través del menú, la app permite entrar en flujos específicos como la gestión de viajes o procesos administrativos definidos en activity_proceso.