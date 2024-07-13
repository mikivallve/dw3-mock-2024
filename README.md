# Instrucciones para el parcial

## Importar el sitio a local by Flywheel (1 pt)
1. Descarga el sitio web de Komo Biosciences de este repositorio.
2. Importa el sitio web a tu entorno local de Flywheel.

## Edita el tema Komo (1pt)
1. Edita el tema Komo para que WordPress te reconozca como autor del tema.
2. Coloca tu número de estudiante como versión del tema

## Crear un usuario Editor de WordPress (2pt)
1. Crea un usuario con el nombre "Keith Bowermaster" y el email "keith@komobiosciences.com".
2. Asigna el rol de "Editor" a este usuario.

## Crear posts (6pts)
1. Crea dos posts utilizando los enlaces proporcionados:
   - [Revolutionary Gene-Editing Startup Komo Biosciences Emerges with Breakthrough Integrase Technology from University of Hawaii](https://biobuzz.io/revolutionary-gene-editing-startup-komo-biosciences-emerges-with-breakthrough-integrase-technology-from-university-of-hawaii/)
   - [Jesse Owens Gene Therapy Breakthrough](https://jabsom.hawaii.edu/news-events/news/2024/07/jesse-owens-gene-therapy-breakthrough.html)
2. Asigna los posts al usuario "Keith Bowermaster".
3. Crea una categoría llamada "Noticias" y asigna los posts a esta categoría.

## Instalar Bootstrap 5.3.3 como dependencia de npm en el tema Komo (2pts)
1. Abre una terminal en la carpeta del tema Komo.
2. Instala Bootstrap 5.3.3 como una dependencia del proyecto.

## Crear archivos SCSS parciales en el tema Komo (6pts)
1. Crea una carpeta llamada "scss" en el tema Komo.
2. Dentro de la carpeta "scss", crea los siguientes archivos parciales:
   - `_comentarios.scss`
   - `_variables.scss`
   - `_generales.scss`
   - `_single-post.scss`
   - `_header.scss`
   - `_pages.scss`
3. Mueve cuidadosamente el CSS que está en el `Customizer` a los archivos parciales correspondientes.

## Crear un archivo SCSS principal que importe los parciales y el CSS de Bootstrap (6pts)
1. Crea un archivo SCSS principal en la carpeta "scss" que se llame `style.scss`.
2. En este archivo, importa todos los archivos parciales creados anteriormente y el CSS de Bootstrap.

## Crear un script en package.json para compilar los archivos SCSS (4pts)
1. Abre el archivo `package.json` en la carpeta del tema Komo.
2. Agrega un script en la sección "scripts" que compile los archivos SCSS a un archivo CSS que WordPress pueda identificar como la hoja de estilos principal.
3. Agrega un segundo script que realice un watch de los archivos SCSS y los compila automáticamente en segundo plano.

## Aplicar los cambios de media queries usando los mixins de Bootstrap (4pts)
1. Reemplaza las reglas de `@media` por los mixins de Bootstrap `media-breakpoint-up()` y/o `media-breakpoint-down()`.

## Aplicar el color primario al fondo del encabezado de escritorio (2pts)
1. Establece el color primario de bootstrap a `#0d1629` 
2. Utiliza esa variable como fondo del elemento `#ast-desktop-header`.

## Modificar el footer (6pts)
1. Agrega el logo de Komo Biosciences en la parte izquierda del footer con un enlace a la página de inicio.
2. Elimina el elemento "Home" del menú en el footer (sin eliminar el elemento del menú principal).
3. Elimina los íconos de Facebook e Instagram de la lista de redes sociales en el footer. Agrega el ícono de LinkedIn.
