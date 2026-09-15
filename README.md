# Web Scraping de Productos

Proyecto desarrollado como parte de una actividad de Web Scraping.

## Objetivo

Crear un scraper capaz de obtener información de productos desde un sitio web.

Para este proyecto se utilizó el sitio Books to Scrape, diseñado para practicar técnicas de Web Scraping.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Requests
- BeautifulSoup
- Pandas

## Funcionamiento

El scraper realiza los siguientes pasos:

1. Realiza una petición HTTP al listado de productos.
2. Utiliza BeautifulSoup para analizar el HTML.
3. Localiza los productos mediante selectores CSS.
4. Obtiene los enlaces hacia las páginas de detalle.
5. Accede automáticamente a cada producto.
6. Extrae título, precio, disponibilidad, categoría y calificación.
7. Almacena los resultados en un DataFrame de Pandas.
8. Exporta los resultados al archivo productos.csv.

## Datos extraídos

- Título
- Precio
- Disponibilidad
- Categoría
- Calificación
- URL del producto

## Resultado

El scraper obtiene información de 20 productos y genera el archivo:

productos.csv

## Autor

Héctor Hugo Hernández
