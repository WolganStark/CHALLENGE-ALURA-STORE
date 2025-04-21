<h1 align="center">Challenge Alura Store</h1>
<p align="center"><img src="https://github.com/user-attachments/assets/7e46e567-7034-4ed2-a068-79952e32f0ce"></p>
<p align="center">El señor Juan tiene cuatro tiendas, y en su intención de saber cual de las cuatro podia vender para reestructurar su negocio, decidió tomar todos los datos que tenia de las tiendas para manipularlos y analizarlos, de manera que se pudiera escoger la tienda más apropiada para su venta</p>

## :hammer:Fases del proyecto y análisis

- `Facturación total de ventas por tienda`: Tomando los datos recibidos por el Sr. Juan, se ha filtrado el DataFrame mediante la librería `pandas` en `Python`. Haciendo uso de un paradigma de programación funcional y de las `Built-in Functions` de Python, se encontró el total de facturación por tienda y mediante el uso de la libreria `matplotlib` se construyó un gráfico para hacer un buen `Data Storytelling`, creando un gráfico de torta `Pie Chart`, mediante el cual se pueden observar los datos de manera gráfica.
<p align="center"><img src="https://github.com/user-attachments/assets/0f4912c9-59db-4dd9-833e-eb61f87ab386"><img src="https://github.com/user-attachments/assets/bf431978-ce67-45bc-bed2-18726904957e"></p>

- `Ventas por categoría`: La siguiente fase del proyecto fue tomar todas las categorías de ventas de las tiendas, filtrarlas y sumar la cantidad de ventas. Todo esto individualizado por tiendas, así encontrando las categorías más y menos populares de cada tienda. En esta fase se hace uso de metodos como `.groupby()`, `.idxmax()` y `,idxmin()`. Se utilizó una gráfica de barras verticales agrupadas por categorías en el eje horizontal, para entender las diferencias de ventas entre las tiendas en la misma categoría.

<p align="center"><img src="https://github.com/user-attachments/assets/83a04c3f-e847-4b2f-9575-56edb8c3b975"></p>

- `Calificación promedio de la tienda`: Esta fase de la manipulación y análisis de datos corresponde a filtrar la columna de calificación del DataFrame, y mediante el uso del metodo `.mean()` encontrar la media de satisfacción de los clientes por tienda. Adicionalmente se empleo un gráfico de barras horizontales, con una paleta de colores tipo ranking, para visualizar los datos de mejor manera.

- `Productos más y menos vendidos`: Haciendo uso de metodos como `.groupby()`, `.sort_values()` y `.count()` se filtran los datos de la columna 'Producto' para encontrar los productos que más se repiten en las tiendas, y crear una lista mediante `list comprehension` para poder tomar valores que se repitieran sin darle más relevancia a un solo producto.

- `Envío promedio por tienda`: En esta fase de manipulación y análisis de los datos, la tarea es filtrar los datos de la columna de 'Costo de envío', para calcular la media de los valores mediante el metodo `.mean()`, de esta manera se pudo evaluar la tienda que tenía una mejor optimización de sus costos de envíos.

- `Desempeño Geográfico`: En construcción... :hammer:

## :white_check_mark:Tecnologías utilizadas
- `Python`: Poderoso lenguaje interpretado, ampliamente utilizado en DataScience.
- `Jupyter Notebooks`: Mediante el uso de Google Colab, accedemos a un notebook para ejecutar código python, sin tener que instalar dependencias en nuestros equipos, siendo una gran herramienta para manejar grandes grupos de datos.
