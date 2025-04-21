<h1 align="center">Challenge Alura Store</h1>
<p align="center"><img src="https://github.com/user-attachments/assets/bb3ea1e2-61c8-4399-8800-3e250d9bb4b5"></p>
<p align="center">El señor Juan tiene cuatro tiendas, y en su intención de saber cual de las cuatro podia vender para reestructurar su negocio, decidió tomar todos los datos que tenia de las tiendas para manipularlos y analizarlos, de manera que se pudiera escoger la tienda más apropiada para su venta</p>

## :hammer:Fases del proyecto y análisis

- `Facturación total de ventas por tienda`: Tomando los datos recibidos por el Sr. Juan, se ha filtrado el DataFrame mediante la librería `pandas` en `Python`. Haciendo uso de un paradigma de programación funcional y de las `Built-in Functions` de Python, se encontró el total de facturación por tienda y mediante el uso de la libreria `matplotlib` se construyó un gráfico para hacer un buen `Data Storytelling`, creando un gráfico de torta `Pie Chart`, mediante el cual se pueden observar los datos de manera gráfica.
<p align="center"><img src="https://github.com/user-attachments/assets/65aa976a-17c7-4ba4-ab1d-747c57c92f39"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a08a2276-25e6-46bb-9782-b5b81ca233fe"></p>

- `Ventas por categoría`: La siguiente fase del proyecto fue tomar todas las categorías de ventas de las tiendas, filtrarlas y sumar la cantidad de ventas. Todo esto individualizado por tiendas, así encontrando las categorías más y menos populares de cada tienda. En esta fase se hace uso de metodos como `.groupby()`, `.idxmax()` y `,idxmin()`. Se utilizó una gráfica de barras verticales agrupadas por categorías en el eje horizontal, para entender las diferencias de ventas entre las tiendas en la misma categoría.

<p align="center"><img src="https://github.com/user-attachments/assets/a6f1b712-b563-44f2-b3b5-33f9f89cd705"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/bf493deb-bd58-4db7-8c33-6132015e3f88"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e0a76ff3-db16-4f19-a879-85c9c17275bd"></p>

- `Calificación promedio de la tienda`: Esta fase de la manipulación y análisis de datos corresponde a filtrar la columna de calificación del DataFrame, y mediante el uso del metodo `.mean()` encontrar la media de satisfacción de los clientes por tienda. Adicionalmente se empleo un gráfico de barras horizontales, con una paleta de colores tipo ranking, para visualizar los datos de mejor manera.

<p align="center"><img src="https://github.com/user-attachments/assets/37fb9f26-6829-4518-80c8-085d298b7e82"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/74d82627-6e58-48dd-8356-bda33c7da132"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/9c3abdd6-a4b5-4534-af20-2c9770d37e1d"></p>

- `Productos más y menos vendidos`: Haciendo uso de metodos como `.groupby()`, `.sort_values()` y `.count()` se filtran los datos de la columna 'Producto' para encontrar los productos que más se repiten en las tiendas, y crear una lista mediante `list comprehension` para poder tomar valores que se repitieran sin darle más relevancia a un solo producto.

<p align="center"><img src="https://github.com/user-attachments/assets/ddcaa385-df26-42ae-9e2e-1f8f54ed7cc9"></p>


- `Envío promedio por tienda`: En esta fase de manipulación y análisis de los datos, la tarea es filtrar los datos de la columna de 'Costo de envío', para calcular la media de los valores mediante el metodo `.mean()`, de esta manera se pudo evaluar la tienda que tenía una mejor optimización de sus costos de envíos.

<p align="center"><img src="https://github.com/user-attachments/assets/354d3350-1003-443b-8030-a6c508326e17"></p>


- `Desempeño Geográfico`: En construcción... :hammer:


## :white_check_mark:Tecnologías y librerias utilizadas
- `Python`: Poderoso lenguaje interpretado, ampliamente utilizado en DataScience.
- `pandas`: Libreria utilizada en Python para el manejo de DataFrames.
- `matplotlib`: Libreria utilizada en Python para la generación de gráficos según los datos analizados.
- `numpy`: Libreria utilizada para la ejecución de calculos matemáticos complejos que no son incluídos nativamente en Python.
- `Jupyter Notebooks`: Mediante el uso de Google Colab, accedemos a un notebook para ejecutar código python, sin tener que instalar dependencias en nuestros equipos, siendo una gran herramienta para manejar grandes grupos de datos.

### :wrench: Como ejecutar el proyecto
1. Debes descargar el archivo del repositorio `AluraStoreLatam.ipynb`, tranquilo no tienes que ejecutarlo en tu maquina.

<p align="center"><img src="https://github.com/user-attachments/assets/247bbc21-365e-47bb-8e8d-a04bb542638c"></p>

2. Abre Google Colab con tu cuenta de Google

<p align="center"><img src="https://github.com/user-attachments/assets/a1c596f2-b2b6-4c46-a479-35cc8b6071fd"></p>

3. Sube el archivo que acabas de descargar

<p align="center"><img src="https://github.com/user-attachments/assets/5ea98394-2513-4ea0-b574-b76a387e2f1d"></p>
   
4. Da click en `Entorno de ejecución` y luego click en ejecutar todo, también puedes usar solo el teclado con el atajo `CTRL + F9`

<p align="center"><img src="https://github.com/user-attachments/assets/bae86cb6-19dd-4afc-8e10-6a3c3eb51a6c"></p>

5. Si deseas también puedes ejecutar cada celda individualmente, simplemente tienes que tener precaución de ejecutar primero la celda de `Importación de datos` ya que es la celda que trae los datos para manipularlos y también importa las librerias y dependencias usadas en el proyecto.

<p align="center"><img src="https://github.com/user-attachments/assets/26ae0542-dc2b-4d90-90b7-6f9a634bdbbf"></p>

Puedes hacer click en la esquina superior izquierda en el simbolo de `play` o puedes utilizar el atajo de teclado `CTRL + ENTER`

6. Ahora estás listo para utilizar esta poderosa herramienta que es Google Colab, y también para explorar con el código de este proyecto, siéntete libre de toquetear el código como tu quieras, este repositorio va a mantenerse funcional para que no tengas miedo de probar cosas distintas.

