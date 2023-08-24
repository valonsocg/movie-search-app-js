# Buscador de Películas

Este proyecto consiste en un buscador de películas implementado en HTML, CSS y JavaScript, que utiliza la API de The Movie Database (TMDb) para obtener información sobre películas y mostrar los resultados en una interfaz web sencilla.

## Componentes Principales

### Interfaz de Usuario (UI)

La interfaz de usuario consta de tres elementos principales:

- Un campo de entrada de texto donde los usuarios pueden escribir el título de la película que desean buscar.
- Un botón "Buscar" que activa la búsqueda cuando se hace clic en él.
- Un contenedor donde se muestran los resultados de la búsqueda.

### Lógica de JavaScript

El archivo `script.js` contiene la lógica de programación necesaria para el funcionamiento del buscador de películas:

- Se agrega un "event listener" al botón "Buscar" que llama a la función `searchMovies()` cuando se hace clic.
- La función `searchMovies()` obtiene el valor del campo de entrada de texto, realiza una solicitud a la API de TMDb utilizando `fetch()` y procesa la respuesta JSON.
- La función `displayMovies()` toma la lista de películas obtenidas de la API y crea elementos HTML dinámicamente para cada película. Estos elementos incluyen el título, la fecha de lanzamiento, una descripción y el póster de la película.
- Los elementos HTML generados dinámicamente se agregan al contenedor de resultados en la página web.

### Estilos CSS

El archivo `style.css` define los estilos visuales aplicados a los elementos en la página web. Esto incluye la disposición de los elementos, colores, fuentes y otros aspectos visuales.

## Uso

1. Abre el archivo `index.html` en tu navegador web.

2. Ingresa el título de una película en el campo de búsqueda.

3. Haz clic en el botón "Buscar".

4. Los resultados de la búsqueda se mostrarán debajo del campo de búsqueda, incluyendo el título, la fecha de lanzamiento, una descripción y el póster de cada película.

## Personalización y Mejoras

- Puedes personalizar los estilos en el archivo `style.css` para adaptar la apariencia del buscador de películas a tus preferencias.
- Si estás interesado en aprender más sobre APIs y cómo trabajar con ellas, podrías explorar otras funciones proporcionadas por la API de TMDb, como obtener más detalles de una película o mostrar recomendaciones basadas en la búsqueda.
- Para un proyecto más completo, podrías implementar la funcionalidad de guardar películas favoritas, agregar reseñas de usuarios o incluir un sistema de calificación.

Este proyecto es un punto de partida para aprender sobre desarrollo web, consumo de APIs y manipulación del DOM en JavaScript. Recuerda revisar la documentación de la API de TMDb para entender mejor las opciones y posibilidades que ofrece. ¡Diviértete explorando y mejorando este buscador de películas!
