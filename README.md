# Portfolio Web — Jorge Pérez López

Repositorio del portfolio personal de **Jorge Pérez López**, Técnico en Sistemas Microinformáticos y Redes y estudiante de 2.º curso del C.F.G.S. de Desarrollo de Aplicaciones Web (DAW) en el CIPFP Mislata.

## Estructura del proyecto

El proyecto está compuesto por los siguientes ficheros en la raíz del repositorio:

```
├── app.js         # Lógica JavaScript para el comportamiento dinámico
├── index.html     # Estructura semántica de la página web
├── README.md      # Documentación del proyecto
└── styles.css     # Hoja de estilos y diseño visual
```

## Explicación del código

### 1. `index.html`
Es el archivo principal de la interfaz. Define toda la estructura semántica de la página utilizando elementos HTML5 modernos:
* Contenedor principal (`.site-wrapper`) estructurado en dos columnas mediante CSS Grid.
* Columna lateral (`.profile-sidebar`) que agrupa la cabecera con el nombre y titulación, los datos de contacto y la barra de navegación lateral (`.sidebar-nav`).
* Área principal (`.main-content`) que contiene las secciones divididas por bloques temáticos: **Perfil Profesional**, **Techné & Competencias** (con tarjetas y etiquetas agrupadas), **Formación en Prácticas** y **Títulos y Estudios**.

### 2. `styles.css`
Contiene la hoja de estilos encargada del diseño visual, paleta de colores y adaptabilidad:
* **Variables CSS (`:root`)**: Define una paleta de colores minimalista en modo oscuro (fondos oscuros, paneles contrastados y acentos en verde esmeralda) junto con las tipografías principales (*Plus Jakarta Sans* y *Fira Code*).
* **Grid y Flexbox**: Distribuye el diseño de dos columnas de manera fija en escritorio y adapta automáticamente los elementos en pantallas pequeñas mediante media queries (`@media`).
* **Componentes visuales**: Estilos específicos para las tarjetas de contenido (`.content-section`, `.timeline-item`), los botones y las etiquetas de texto (`.badge`, `.pill`).

### 3. `app.js`
Script en JavaScript nativo (Vanilla JS) que añade interactividad a la navegación:
* Utiliza el evento `DOMContentLoaded` para asegurar que el DOM está completamente cargado antes de ejecutar el código.
* Implementa un escuchador de eventos en el scroll (`window.addEventListener("scroll")`) que evalúa la posición vertical de la página frente a cada sección.
* Compara el desplazamiento actual para añadir o quitar dinámicamente la clase `.active` al enlace correspondiente del menú lateral, permitiendo resaltar visualmente en qué sección se encuentra navegando el usuario en todo momento.

## Despliegue

Al tratarse de un sitio web estático sin dependencias ni compiladores, puede visualizarse abriendo directamente `index.html` en el navegador o publicarse de forma gratuita a través de **GitHub Pages**.

## Contacto

* **Ubicación:** Mislata, Valencia (España)
* **Email:** [perezlopezj07@hotmail.com](mailto:perezlopezj07@hotmail.com)
* **LinkedIn:** [linkedin.com/in/jorge-pérez-lópez](https://linkedin.com/in/jorge-p%C3%A9rez-l%C3%B3pez/)
* **GitHub:** [github.com/jorperlo](https://github.com/jorperlo)