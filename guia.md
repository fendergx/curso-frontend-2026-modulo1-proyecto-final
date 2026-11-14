Curso: Desarrollo en JavaScript 

Modulo 1 : Fundamentos de Desarrollo Web 

Evaluación Final: Sitio web responsive publicado en GitHub Pages. 

### Objetivos 

1. Diseñar y estructurar una Landing Page para un servicio profesional o portafolio personal, aplicando los fundamentos de desarrollo web y buenas prácticas de HTML semántico. 

2. Implementar y optimizar el diseño responsivo de la Landing Page, incorporando estilos y validaciones de entradas de datos como nociones básicas de seguridad web. 

3. Publicar y desplegar la Landing Page en la web utilizando Git y GitHub Pages, verificando su funcionamiento y accesibilidad desde diferentes dispositivos. 

# 1. Requerimientos Estructurales 

El sitio web debe contar con un menú de navegación global (```<nav>```) que permita al usuario moverse fluidamente entre cuatro (4) páginas HTML distintas, compartiendo todas una hoja de estilos común (style.css). 

A. Página de Inicio (index.html) 

- Propósito: Bienvenida e introducción al portafolio. 

- Requerimientos: Debe utilizar etiquetas semánticas para generar una maqueta que incluya cabecera, cuerpo, panel lateral, secciones y pie de página (```<header>, <main>, <aside>, <section>, <footer>```) y un botón que dirija a la página de proyectos. 

B. Página "Acerca de" (acerca.html) 

- Propósito: Perfil profesional o académico del estudiante (incluir su fotografía). 

- Requerimientos: Uso adecuado de jerarquía de encabezados (```<h1>, <h2>```) y listas (```<ul> o <ol>```) para detallar habilidades, herramientas manejadas y áreas de interés. 

C. Página de Proyectos (proyectos.html) 

- Propósito: Mostrar los trabajos realizados a través de datos tabulares (pueden ser ficticios o reales). 

- Requerimientos: Implementar una Tabla HTML que contenga al menos 4 filas de datos y 4 columnas (Ej. Nombre del Proyecto, Tecnologías, Fecha, Estado). La tabla debe usar las etiquetas semánticas correctas (```<thead>, <tbody>, <th>, <tr>, <td>```) y ser legible en dispositivos móviles (responsiva).

D. Página de Contacto (contacto.html) 

- Propósito: Interfaz de comunicación con validaciones de seguridad. 

- Requerimientos: Un formulario que incluya, como mínimo, los siguientes controles: 

- Campos de texto (text, email) con atributo required. 

- Campo de contraseña temporal (password) con minlength. 

- Menú desplegable (select). 

- Botones de opción (radio) y casillas de verificación (checkbox, ej. para aceptar términos y condiciones). 

- Carga de archivos (file) limitando las extensiones permitidas usando el atributo accept. 

- Área de texto (textarea). 

# 2. Requerimientos de Diseño y Seguridad (CSS y Buenas Prácticas) 

- Diseño Responsivo: El sitio debe adaptarse a dispositivos móviles (mobile first), tablets y escritorio utilizando Flexbox/Grid y al menos dos puntos de quiebre (Media Queries con minwidth o max-width). 

- Uso de Media Queries (@media) para adaptar el contenido (ej. columnas que colapsan a 1 sola en móviles y se expanden a 2 o 3 en desktop). 

- Aplicar el concepto de "Validación y desinfección de inputs": Validaciones por atributos HTML5 en el formulario (required, type="email", maxlength). 

- Evitar el uso de estilos en línea; todo el CSS debe estar en un archivo externo para cumplir con las bases de la Política de Seguridad de Contenidos (CSP). 

- Investigar como Incluir un meta tag de Content Security Policy (CSP) en el ```<head>```. 

- Investigar el uso de metodología BEM (Bloque, Elemento, Modificador): Uso recomendado de esta convención para nombrar las clases de CSS de forma estructurada y modular. 

# 3. Control de Versiones y Despliegue (Git / GitHub) 

El estudiante debe evidenciar el flujo de trabajo correcto: 

1. Inicializar el repositorio (git init). 

2. Realizar al menos tres (3) commits descriptivos durante el proceso. 

3. Vincular el repositorio remoto (git remote add origin). 

4. Publicar los cambios (git push -u origin main). 

5. Habilitar el despliegue estático desde los ajustes del repositorio (GitHub Pages). 

