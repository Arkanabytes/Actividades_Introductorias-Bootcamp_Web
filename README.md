# Actividades_Introductorias-Bootcamp_Web

🚀 Soluciones Actividades Introductorias – Bootcamp Web
✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?
Sitios Web Informativos:

Wikipedia - Presenta información estática organizada, principalmente lectura
BBC News - Portal de noticias con artículos y contenido informativo
Blog personal de un desarrollador - Contenido estático con posts y artículos

Aplicaciones Web:

Gmail - Gestión de correos, envío, organización, filtros
Trello - Gestión de proyectos con tableros interactivos
Spotify Web - Reproducción de música, playlists, búsqueda

Justificación:

Sitios web: Su función principal es mostrar información. La interacción es mínima (navegación, búsqueda básica).
Aplicaciones web: Permiten al usuario realizar tareas complejas, manipular datos, tienen estados persistentes y funcionalidades avanzadas.

Reflexión:
Una aplicación web es interactiva porque:

Responde a acciones del usuario en tiempo real
Mantiene estado y datos del usuario
Procesa información y genera respuestas dinámicas
Tecnologías: JavaScript, APIs, bases de datos, frameworks como React/Angular


✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna
Conceptos:
Frontend (Cliente)

Interfaz de usuario visible
Tecnologías: HTML, CSS, JavaScript, React, Angular
Se ejecuta en el navegador del usuario

Backend (Servidor)

Lógica de negocio y procesamiento de datos
Tecnologías: Node.js, Java, Python, PHP
Maneja autenticación, APIs, reglas de negocio

Base de Datos

Almacenamiento persistente de información
Tecnologías: MySQL, PostgreSQL, MongoDB
Guarda datos de usuarios, contenido, configuraciones

Diagrama de Comunicación:
┌─────────────┐    HTTP Request    ┌─────────────┐    SQL Query    ┌─────────────┐
│   Frontend  │ ────────────────► │   Backend   │ ──────────────► │   Database  │
│             │                   │             │                 │             │
│ HTML/CSS/JS │ ◄──────────────── │ Java/Node.js│ ◄────────────── │ MySQL/Postgres│
│             │    HTTP Response  │             │   Result Set    │             │
└─────────────┘                   └─────────────┘                 └─────────────┘
       ▲                                                                   
       │                                                                   
       ▼                                                                   
┌─────────────┐                                                           
│   Usuario   │                                                           
│  (Browser)  │                                                           
└─────────────┘
Flujo de datos:

Usuario interactúa con Frontend
Frontend envía petición HTTP al Backend
Backend procesa y consulta Base de Datos
Base de Datos retorna información
Backend envía respuesta al Frontend
Frontend actualiza la interfaz para el Usuario


✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo
Cómo abrir DevTools:

Windows: F12 o Ctrl + Shift + I
Linux: Ctrl + Shift + I
Mac: Cmd + Option + I

Pestañas principales:
Elements (Elementos)

Inspecciona y modifica HTML/CSS en tiempo real
Útil para debugging de estilos y estructura

Console (Consola)

Muestra errores JavaScript
Permite ejecutar código JS directamente
Logs de la aplicación

Network (Red)

Monitorea todas las solicitudes HTTP
Muestra tiempos de carga
Útil para optimización de rendimiento

Storage (Almacenamiento)

LocalStorage, SessionStorage, Cookies
Datos almacenados en el navegador

Ejemplo de inspección en Google:
Solicitud HTTP en pestaña Network:
Request URL: https://www.google.com/search?q=bootcamp
Request Method: GET
Status Code: 200 OK
Response Time: 150ms
Content-Type: text/html; charset=UTF-8
Error típico en Console:
Error: Cannot read property 'addEventListener' of null
    at script.js:5:23
Elemento HTML inspeccionado:
html<input type="text" name="q" value="bootcamp" 
       class="gLFyf gsfi" maxlength="2048">

✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?
Tecnologías Web Fundamentales:
HTML (HyperText Markup Language)

Define la estructura y contenido de la página
Elementos como <h1>, <p>, <div>, <img>
Es el "esqueleto" de la web

html<h1>Mi primera página</h1>
<p>Este es un párrafo de texto.</p>
CSS (Cascading Style Sheets)

Controla la presentación visual
Colores, fonts, layout, animaciones
Es el "diseño" de la web

cssh1 {
    color: blue;
    font-size: 24px;
}
JavaScript

Añade interactividad y funcionalidad
Maneja eventos, manipula DOM, hace peticiones
Es el "comportamiento" de la web

javascriptdocument.getElementById('button').addEventListener('click', function() {
    alert('¡Hola mundo!');
});
Diferencias clave Java vs JavaScript:
AspectoJavaJavaScriptCompilaciónCompilado (.class)InterpretadoTipadoEstáticoDinámicoEjecuciónJVMNavegador/Node.jsDeclaraciónint numero = 5;let numero = 5;Funciónpublic void metodo()function metodo()SalidaSystem.out.println()console.log()Uso principalBackend/DesktopFrontend/Web

✅ ACTIVIDAD 5 – Explorando el stack web por equipos
Guía por Equipo:
Equipo 1 - HTML

Estructura semántica
Etiquetas principales
Formularios y validación
Accesibilidad

Equipo 2 - CSS

Selectores y propiedades
Flexbox y Grid
Responsive design
Animaciones

Equipo 3 - JavaScript

Variables y funciones
DOM manipulation
Eventos
Async/await

Equipo 4 - React

Componentes y JSX
State y props
Hooks
Virtual DOM

Equipo 5 - Node.js / Maven

Servidor JavaScript
NPM packages
APIs REST
Gestión de dependencias

Equipo 6 - Java + Spring Boot

Framework backend
Controladores REST
Inyección de dependencias
Seguridad

Equipo 7 - MySQL / PostgreSQL

Bases de datos relacionales
Consultas SQL
Índices y optimización
Transacciones

Presentación sugerida por equipo:

¿Qué es y para qué sirve?
Ventajas principales
Ejemplo práctico simple
Cómo se conecta con otras tecnologías del stack


📝 Notas Adicionales
Stack Tecnológico Completo:
┌─────────────────────────────────────────────────────────────┐
│                      FULL STACK WEB                        │
├─────────────────────────────────────────────────────────────┤
│ Frontend:  HTML + CSS + JavaScript + React                 │
│ Backend:   Java + Spring Boot + Node.js                    │
│ Database:  MySQL / PostgreSQL                              │
│ Tools:     Maven, NPM, Git, VS Code                        │
└─────────────────────────────────────────────────────────────┘
Próximos Pasos:

Configurar entorno de desarrollo
Primer proyecto "Hello World"
Integración de tecnologías
Despliegue básico

¡Estas actividades sientan las bases para un aprendizaje sólido en desarrollo web full-stack!
