# Proyecto Integrador 1  

## Alumno: Ojeda Alvaro
### Actividad Práctica Evaluable 04 – Flexbox y Media Queries

**Fecha de entrega:** próxima clase sincrónica.  
**Modalidad:** Individual – Se controlará que cada trabajo sea una creación única con diseño, temática y contenido original generado o recopilado por cada alumno.

---

## Ejercicio Práctico: Construcción de una Página Web Responsiva usando Flexbox y Media Queries

### Objetivo:
El objetivo de este ejercicio es practicar la maquetación de una página web utilizando **CSS Flexbox** y **Media Queries**.  
Deben crear una página que contenga títulos, párrafos e imágenes, y que se adapte de manera responsiva a diferentes tamaños de pantalla.  
Deben utilizar prioritariamente **Flexbox** y sus propiedades, evitando cualquier otro modo de manejar tamaños y posiciones de los elementos, salvo que Flexbox no cuente con una propiedad adecuada para tal fin.

---

### Instrucciones:

#### 1. Estructura HTML:
- Crear un archivo `index.html` con la estructura básica de un documento HTML5.
- Incluir los siguientes elementos dentro del `<body>`:
  - Un `<header>` con un título (`<h1>`) de la página.
  - Una sección `<section>` que contenga tres artículos (`<article>`):
    - Cada `<article>` debe tener:
      - Un título (`<h2>`).
      - Un párrafo (`<p>`) con texto descriptivo.
      - Una imagen (`<img>`) relacionada con el contenido del artículo.
      - Cada imagen debe ser un vínculo (`<a>`) que muestra la imagen en una nueva página, donde ocupe todo el ancho de la pantalla, acompañada de su título y párrafo descriptivo, manteniendo la propiedad responsiva.
  - Un `<footer>` con un párrafo (`<p>`) con texto de pie de página.

#### 2. Estilos CSS:
- Crear un archivo `styles.css` y vincularlo en el `<head>` del documento HTML.
- Utilizar **Flexbox** para alinear los elementos dentro de cada `<article>` y organizar los artículos dentro de la sección.
- Aplicar estilos básicos a los títulos, párrafos e imágenes para mejorar la presentación.
- Configurar las imágenes para que sean fluidas y no excedan el ancho del contenedor.

#### 3. Media Queries:
- Usar **Media Queries** para adaptar el diseño a diferentes tamaños de pantalla:
  - **Pantallas pequeñas** (menos de 600px de ancho):
    - Los artículos deben apilarse en una sola columna.
    - Asegurarse de que el texto y las imágenes sean legibles.
  - **Pantallas medianas** (entre 600px y 900px de ancho):
    - Los artículos deben mostrarse en dos columnas.
    - Ajustar el tamaño del texto e imágenes para adaptarse al espacio disponible.
  - **Pantallas grandes** (más de 900px de ancho):
    - Los artículos deben mostrarse en tres columnas.
    - Aplicar un espacio uniforme entre las columnas y ajustar el contenido para mejor legibilidad.

#### 4. Contenido:
- El tema y contenido de la página puede elegirse libremente, pero deben incluir al menos 150 palabras por párrafo y que las imágenes sean relevantes.

#### 5. Entrega:
- Cada alumno debe entregar el link a un repositorio en GitHub que contenga la carpeta del proyecto con los archivos `index.html`, `styles.css`, y una subcarpeta con las imágenes utilizadas.

---

### Puntos de Evaluación:
- Correcta implementación de Flexbox para la distribución del contenido.
- Uso efectivo de Media Queries para la adaptabilidad en diferentes dispositivos.
- Calidad y claridad del código (comentarios, buena organización de las reglas CSS, etc.).
- Presentación visual del diseño.

Este ejercicio les proporcionará una práctica integral en la creación de layouts responsivos, preparándolos para desarrollar sitios web modernos y adaptativos.
