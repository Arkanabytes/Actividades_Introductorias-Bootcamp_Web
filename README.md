# Actividades_Introductorias-Bootcamp_Web

## ✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?

**🎯 Objetivo:** Comprender la diferencia entre un sitio web estático y una aplicación web interactiva.

### 1. Ejemplos de sitios web informativos:
- [Wikipedia](https://www.wikipedia.org/)
- [BBC News](https://www.bbc.com/)
- [Medium](https://medium.com/)

### 2. Ejemplos de aplicaciones web:
- [Gmail](https://mail.google.com/)
- [Trello](https://trello.com/)
- [Spotify Web](https://open.spotify.com/)

### 3. Justificación:

| Tipo                | Características clave                                                        | Ejemplos                     |
|---------------------|------------------------------------------------------------------------------|------------------------------|
| **Sitio web**       | Contenido estático, informativo, sin necesidad de iniciar sesión.           | Wikipedia, BBC News, Medium  |
| **Aplicación web**  | Interactiva, permite acciones del usuario, autenticación, datos en tiempo real. | Gmail, Trello, Spotify       |

Los sitios informativos presentan información fija o actualizada por administradores, pero no requieren interacción avanzada del usuario. Las apps web permiten enviar correos, crear tareas, reproducir música, etc.

### 4. Reflexión:

Una aplicación web es interactiva porque:
- El usuario puede realizar acciones dinámicas (como escribir, subir, o modificar contenido).
- No siempre necesita recargar toda la página.
- Cambia su interfaz según lo que haga el usuario.

**Tecnologías comunes detrás:**
- **Frontend:** HTML, CSS, JavaScript, React, Vue, Angular
- **Backend:** Node.js, Java (Spring), Python (Django/Flask)
- **APIs:** REST, GraphQL
- **Base de datos:** MySQL, PostgreSQL, MongoDB

---

## ✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna

**🎯 Objetivo:** Comprender los componentes principales de una app web (frontend, backend, base de datos).

### 1. Definiciones:

- **Frontend:** Es la parte visual con la que interactúa el usuario. Se compone de HTML, CSS y JavaScript. Es lo que ves en el navegador.
- **Backend:** Parte lógica del servidor. Se encarga de procesar peticiones, manejar datos y comunicarse con la base de datos. Lenguajes comunes: Java, Node.js, Python.
- **Base de datos:** Sistema donde se almacenan los datos (usuarios, productos, comentarios, etc.). Ejemplos: MySQL, MongoDB, PostgreSQL.

### 2. Diagrama en Mermaid:

```mermaid
graph LR
A[Usuario] --> B[Frontend (HTML/CSS/JS)]
B --> C[Backend (API - Node.js/Spring)]
C --> D[Base de Datos (MySQL/MongoDB)]
D --> C
C --> B
B --> A

✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo
🎯 Objetivo: Familiarizarse con las DevTools del navegador.

1. ¿Cómo abrir DevTools?
Windows: F12 o Ctrl + Shift + I

Linux: Ctrl + Shift + I

Mac: Cmd + Option + I

2. Pestañas importantes a explorar:
Elementos: Muestra el HTML y cómo se estructura visualmente la página.

Consola: Muestra errores y mensajes generados por JavaScript.

Red (Network): Permite ver las solicitudes HTTP (peticiones y respuestas del servidor).

Almacenamiento (Storage): Muestra cookies, localStorage, sessionStorage, etc.

3. Capturas sugeridas (ejemplo con google.com):
Solicitud HTTP: Ve a la pestaña Red, recarga la página y haz clic en un archivo .html, .js o .json.

Error en consola: Si no aparece ninguno, puedes simular uno escribiendo en consola:

js
Copiar
Editar
console.error("Error de prueba");
HTML de un elemento: Haz clic derecho sobre el logo de Google > "Inspeccionar", y verás su etiqueta <img> o <div> en el panel de Elementos.

✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?
🎯 Objetivo: Dar una primera mirada sencilla a HTML, CSS y JavaScript.

1. ¿Qué hace cada tecnología?
HTML (HyperText Markup Language): Define la estructura de una página web. Usa etiquetas como <h1>, <p>, <a>, etc.

CSS (Cascading Style Sheets): Estiliza el contenido HTML (colores, tamaños, márgenes, etc.).

JavaScript (JS): Añade interactividad (como responder a clics, mostrar mensajes, cargar contenido sin recargar la página).

2. Comparación: Java vs JavaScript
Característica	Java	JavaScript
Tipo de lenguaje	Compilado	Interpretado por el navegador
Entorno	Backend (apps, servidores, móviles)	Navegador (frontend) y backend (Node.js)
Sintaxis similar	Sí (ambos usan llaves y variables)	Sí, pero no son compatibles
Relación	Ninguna directa	Nombre similar, pero tecnologías distintas

3. Mini README: Tecnologías Web
markdown
Copiar
Editar
# Tecnologías Básicas Web

## HTML
Es el lenguaje que define la **estructura** de una página web.

```html
<h1>Hola Mundo</h1>
<p>Bienvenido a mi sitio web.</p>
CSS
Define la apariencia visual de los elementos HTML.

css
Copiar
Editar
h1 {
  color: blue;
  font-family: Arial;
}
JavaScript
Agrega interactividad a una web.

js
Copiar
Editar
document.querySelector("h1").onclick = () => {
  alert("¡Haz hecho clic en el título!");
};
yaml
Copiar
Editar

---

¿Te gustaría que continúe con la Actividad 5 también? Puedo ayudarte con la presentación para el tema que te haya tocado en tu equipo.



Dijiste:
pero todo


ChatGPT dijo:
Perfecto, aquí tienes el documento completo de las actividades 1 a 5 ya desarrolladas, en formato Markdown con todo lo investigado, ejemplos, justificaciones, diagramas y código. Puedes copiarlo directamente a tu archivo README.md o subirlo a tu repositorio de GitHub:

markdown
Copiar
Editar
# 🚀 Actividades Introductorias – Bootcamp Web

Este README contiene 5 actividades diseñadas para introducir a los estudiantes al mundo del desarrollo web, partiendo desde los fundamentos de redes hasta las tecnologías modernas del stack completo.

---

## ✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?

**🎯 Objetivo:** Comprender la diferencia entre un sitio web estático y una aplicación web interactiva.

### 1. Ejemplos de sitios web informativos:
- [Wikipedia](https://www.wikipedia.org/)
- [BBC News](https://www.bbc.com/)
- [Medium](https://medium.com/)

### 2. Ejemplos de aplicaciones web:
- [Gmail](https://mail.google.com/)
- [Trello](https://trello.com/)
- [Spotify Web](https://open.spotify.com/)

### 3. Justificación:

| Tipo                | Características clave                                                        | Ejemplos                     |
|---------------------|------------------------------------------------------------------------------|------------------------------|
| **Sitio web**       | Contenido estático, informativo, sin necesidad de iniciar sesión.           | Wikipedia, BBC News, Medium  |
| **Aplicación web**  | Interactiva, permite acciones del usuario, autenticación, datos en tiempo real. | Gmail, Trello, Spotify       |

Los sitios informativos presentan información fija o actualizada por administradores, pero no requieren interacción avanzada del usuario. Las apps web permiten enviar correos, crear tareas, reproducir música, etc.

### 4. Reflexión:

Una aplicación web es interactiva porque:
- El usuario puede realizar acciones dinámicas (como escribir, subir, o modificar contenido).
- No siempre necesita recargar toda la página.
- Cambia su interfaz según lo que haga el usuario.

**Tecnologías comunes detrás:**
- **Frontend:** HTML, CSS, JavaScript, React, Vue, Angular
- **Backend:** Node.js, Java (Spring), Python (Django/Flask)
- **APIs:** REST, GraphQL
- **Base de datos:** MySQL, PostgreSQL, MongoDB

---

## ✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna

**🎯 Objetivo:** Comprender los componentes principales de una app web (frontend, backend, base de datos).

### 1. Definiciones:

- **Frontend:** Es la parte visual con la que interactúa el usuario. Se compone de HTML, CSS y JavaScript. Es lo que ves en el navegador.
- **Backend:** Parte lógica del servidor. Se encarga de procesar peticiones, manejar datos y comunicarse con la base de datos. Lenguajes comunes: Java, Node.js, Python.
- **Base de datos:** Sistema donde se almacenan los datos (usuarios, productos, comentarios, etc.). Ejemplos: MySQL, MongoDB, PostgreSQL.

### 2. Diagrama en Mermaid:

```mermaid
graph LR
A[Usuario] --> B[Frontend (HTML/CSS/JS)]
B --> C[Backend (API - Node.js/Spring)]
C --> D[Base de Datos (MySQL/MongoDB)]
D --> C
C --> B
B --> A
Visualízalo en https://mermaid.live

✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo
🎯 Objetivo: Familiarizarse con las DevTools del navegador.

1. ¿Cómo abrir DevTools?
Windows: F12 o Ctrl + Shift + I

Linux: Ctrl + Shift + I

Mac: Cmd + Option + I

2. Pestañas importantes a explorar:
Elementos: Muestra el HTML y cómo se estructura visualmente la página.

Consola: Muestra errores y mensajes generados por JavaScript.

Red (Network): Permite ver las solicitudes HTTP (peticiones y respuestas del servidor).

Almacenamiento (Storage): Muestra cookies, localStorage, sessionStorage, etc.

3. Capturas sugeridas (ejemplo con google.com):
Solicitud HTTP: Ve a la pestaña Red, recarga la página y haz clic en un archivo .html, .js o .json.

Error en consola: Si no aparece ninguno, puedes simular uno escribiendo en consola:

js
Copiar
Editar
console.error("Error de prueba");
HTML de un elemento: Haz clic derecho sobre el logo de Google > "Inspeccionar", y verás su etiqueta <img> o <div> en el panel de Elementos.

✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?
🎯 Objetivo: Dar una primera mirada sencilla a HTML, CSS y JavaScript.

1. ¿Qué hace cada tecnología?
HTML (HyperText Markup Language): Define la estructura de una página web. Usa etiquetas como <h1>, <p>, <a>, etc.

CSS (Cascading Style Sheets): Estiliza el contenido HTML (colores, tamaños, márgenes, etc.).

JavaScript (JS): Añade interactividad (como responder a clics, mostrar mensajes, cargar contenido sin recargar la página).

2. Comparación: Java vs JavaScript
Característica	Java	JavaScript
Tipo de lenguaje	Compilado	Interpretado por el navegador
Entorno	Backend (apps, servidores, móviles)	Navegador (frontend) y backend (Node.js)
Sintaxis similar	Sí (ambos usan llaves y variables)	Sí, pero no son compatibles
Relación	Ninguna directa	Nombre similar, pero tecnologías distintas

3. Mini README: Tecnologías Web
markdown
Copiar
Editar
# Tecnologías Básicas Web

## HTML
Es el lenguaje que define la **estructura** de una página web.

```html
<h1>Hola Mundo</h1>
<p>Bienvenido a mi sitio web.</p>
CSS
Define la apariencia visual de los elementos HTML.

css
Copiar
Editar
h1 {
  color: blue;
  font-family: Arial;
}
JavaScript
Agrega interactividad a una web.

js
Copiar
Editar
document.querySelector("h1").onclick = () => {
  alert("¡Haz hecho clic en el título!");
};
yaml
Copiar
Editar

---

## ✅ ACTIVIDAD 5 – Explorando el stack web por equipos

**🎯 Objetivo:** Conocer las principales tecnologías del stack web a trabajar en el bootcamp.

### 1. Reparto de temas por equipo:

| Equipo | Tema                         |
|--------|------------------------------|
| 1      | HTML                         |
| 2      | CSS                          |
| 3      | JavaScript                   |
| 4      | React                        |
| 5      | Node.js / Maven              |
| 6      | Java + Spring Boot           |
| 7      | MySQL / PostgreSQL           |

### 2. Indicaciones para la presentación:
- Crear una presentación sencilla en [https://gamma.app](https://gamma.app) (o similar).
- Máximo **5 slides** con:
  - ¿Qué es?
  - ¿Para qué sirve?
  - ¿Dónde se usa?
  - Imagen o diagrama explicativo
  - ¿Por qué es importante?

### 3. Exposición:
- Solo **una persona** del equipo presenta.
- Tiempo máximo: **3 minutos**.

---

¡Fin del documento! 🚀
