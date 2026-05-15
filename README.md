# LS45 Automotriz

Sitio web para LS45 Automotriz, empresa chilena de compra y venta de vehículos seminuevos y usados.

## Secciones del sitio

- Vehículos disponibles (con filtros y galería)
- Servicios
- Información de la empresa
- Blog
- Contacto

## Decisiones de diseño

### ¿Por qué creamos el archivo ls45-custom.css?

Cuando empezamos a trabajar con la plantilla que nos dieron como base, nos dimos cuenta de que hacer cambios directamente en el CSS original podía volverse un caos. Si modificábamos el style.css principal y después necesitábamos actualizar la plantilla, se perdían todos los cambios.

Entonces decidimos crear un archivo separado llamado `ls45-custom.css` donde fuimos metiendo todas las personalizaciones que necesitábamos. Esto nos permite:

- No tocar el CSS original de la plantilla (así podemos actualizarlo si sale una nueva versión)
- Tener todos nuestros cambios organizados en un solo lugar
- Saber exactamente qué modificamos sin necesidad de comparar archivos

### ¿Qué contiene ls45-custom.css?

Básicamente es un archivo con mejoras pequeñas pero importantes:

- Botones flotantes de redes sociales (Facebook, Instagram, WhatsApp) en la esquina inferior derecha
- Mejoras en el header para que el logo y el menú queden mejor alineados
- Efecto futurista con degradado azulado en el hero
- Ajuste del formulario de búsqueda para que quede más a la derecha
- Cards de vehículos con hover y uniformidad en las alturas
- Ajustes en la sección "Por qué elegirnos" y servicios
- Mejoras en el footer para que los textos se lean bien sobre el fondo oscuro
- Adaptación para móviles (responsive)
- Navbar translúcido al hacer scroll
- Cards clickeables en CTA (compra/vende tu vehículo)
- Botones copiables en la sección de contacto

## Estructura del proyecto

Seguimos la estructura que venía con la plantilla original:

- `index.html` - Archivo principal con todo el contenido
- `css/` - Archivos de estilos (incluyendo ls45-custom.css)
- `sass/` - Archivos SCSS modulares
- `img/` - Imágenes organizadas por secciones
- `js/` - Archivos JavaScript

Dentro de `sass/` están los archivos SCSS separados por componentes: `_header.scss`, `_hero.scss`, `_car.scss`, `_footer.scss`, `_services.scss`, etc.

## Cambios recientes realizados

- Se eliminaron los botones "Contáctanos" y "Ver Servicios" de la sección Inicio
- Se eliminó la sección "¿Por qué elegirnos?"
- Se eliminó la topbar con datos de contacto del header
- Se hicieron clickeables las cards de "Compra tu Vehículo" y "Vende tu Vehículo" (ahora solo muestran imagen)
- Se agregaron botones copiables en la sección contactanos (Jimmy, Jhoanna y Email)
- Se eliminaron los números de teléfono escritos en el footer
- Se implementó navbar estático pero translúcido al hacer scroll

## Equipo

Este proyecto se hizo en grupo de 6 integrantes.

## Ver el sitio

**Url a Netlify:** https://heartfelt-licorice-750b4b.netlify.app/#contacto