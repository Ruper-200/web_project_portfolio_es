# Portafolio de Ruperto Bonilla Arceo

Portafolio profesional orientado a oportunidades como **Front-End / Web Developer Junior**. Presenta mis proyectos formativos, habilidades técnicas, formación actual y vías de contacto. Comenzó como una práctica de maquetación y evolucionó para apoyar mi búsqueda de empleo.

## Sitio publicado

[Ver portafolio](https://ruper-200.github.io/web_project_portfolio_es/)

La URL muestra la versión desplegada en GitHub Pages; los cambios locales solo estarán disponibles allí después de su publicación.

## Tecnologías del sitio

- HTML5 semántico y CSS3.
- CSS Grid, Flexbox y media queries.
- Fuentes locales Open Sans y Archivo Black.
- Git y GitHub para control de versiones; GitHub Pages para publicación.

El portafolio es estático: no requiere JavaScript, instalación de dependencias ni compilación. Las tecnologías indicadas en cada tarjeta corresponden al proyecto presentado, no necesariamente a este sitio.

## Estructura

```text
index.html             # Perfil, proyectos, habilidades, formación y contacto
styles/index.css       # Punto de entrada de estilos
styles/normalize.css   # Normalización entre navegadores
styles/styles.css      # Fuentes, componentes y adaptación responsive
images/                # Fotografía, capturas e iconos existentes
fonts/                 # Fuentes locales WOFF2 y WOFF
favicon.ico            # Icono del sitio
```

## Proyectos presentados

- [Around The U.S.](https://github.com/Ruper-200/web_project_around_es): aplicación interactiva formativa con TypeScript y consumo de una API REST. Es el proyecto principal. No se muestra un botón de demo mientras no haya un despliegue público verificado.
- [Página de una cafetería](https://github.com/Ruper-200/web_project_coffeeshop_es): maquetación con HTML y CSS y formulario con validación nativa. [Demo pública](https://ruper-200.github.io/web_project_coffeeshop_es/).

## Responsive y accesibilidad

El diseño conserva la identidad oscura y los acentos violetas. Utiliza columnas flexibles en escritorio, ajustes hasta 1023 px para tablet y una columna hasta 767 px para móvil. Las tarjetas, etiquetas y enlaces se adaptan al ancho disponible.

Incluye navegación por secciones, enlace para saltar al contenido, jerarquía de encabezados, textos alternativos, foco visible y enlaces de contacto identificables. Las fuentes usan `font-display: swap` y las capturas se cargan de forma diferida.

## Cómo visualizarlo

1. Clona el repositorio y abre su carpeta.
2. Abre `index.html` en un navegador; no hace falta compilar.
3. También puedes usar un servidor estático local. Si tienes Python, ejecuta `python -m http.server 8000` y visita `http://localhost:8000`.

Las rutas de estilos, fuentes e imágenes son relativas para funcionar bajo `/web_project_portfolio_es/` en GitHub Project Pages.

## Mantenimiento

Mantener las descripciones respaldadas por los proyectos y comprobar las demos antes de incorporarlas. El enlace para descargar CV se omite hasta disponer de un PDF definitivo; cuando exista, puede añadirse a la lista `profile__nav-links` con una ruta relativa al archivo real.

## Autor

**Ruperto Bonilla Arceo** · Cancún, México

- [GitHub](https://github.com/Ruper-200)
- [LinkedIn](https://www.linkedin.com/in/erick-ruperto-bonilla-arceo/)
- [Email](mailto:erickoboae@gmail.com)
