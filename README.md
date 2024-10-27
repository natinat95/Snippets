# HTML Snippets para Visual Studio Code

Este archivo incluye dos Snippets personalizados para Visual Studio Code en HTML, diseñados para optimizar el flujo de trabajo en proyectos web. Cada Snippet cubre una estructura común: un `header` básico con un menú de navegación y los metadatos necesarios para Google Bot en el `head` del documento.

## Snippets

### 1. Basic HTML Header

- **Prefijo**: `htmlheader`
- **Descripción**: Este Snippet genera una estructura básica de un `header` con un enlace para el logo o nombre de la marca, y un menú de navegación con enlaces comunes.
- **Estructura**:
   ```html
   <header>
      <nav>
         <a href="#">{{ Logo o Nombre de Marca }}</a>
         <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
         </ul>
      </nav>
   </header>
### 2. Google Bot Meta Tags

- **Prefijo**: `metagoogle`
- **Descripción**: Snippet para añadir metadatos básicos en el `head` del documento HTML, optimizados para el SEO y la indexación por parte de Google Bot.
- **Estructura**:
   ```html
   <meta name="description" content="{{ Descripción del sitio }}">
   <meta name="keywords" content="{{ Palabras clave }}">
   <meta name="author" content="{{ Nombre del autor }}">
   <meta name="robots" content="{{ index,follow | noindex,nofollow }}">
   <meta name="googlebot" content="{{ index,follow | noindex,nofollow }}">
