Análisis de Ventas en Línea 🚀
Este proyecto analiza un dataset de ventas en línea con el objetivo de extraer información valiosa sobre las tendencias de ventas, clientes y productos, así como identificar patrones que podrían ser útiles para mejorar las estrategias comerciales.

Tabla de Contenidos
Descripción del Proyecto
Dataset
Requisitos
Ejecución del Proyecto
Análisis Realizado
Resultados Clave
Visualizaciones
Autor
Descripción del Proyecto
Este proyecto utiliza herramientas de Python para realizar un análisis exploratorio de datos (EDA) sobre un dataset de ventas en línea. Las librerías empleadas incluyen:

Pandas: para manipulación y análisis de datos.
NumPy: para cálculos numéricos.
Matplotlib y Seaborn: para visualización de datos.
Dataset
El dataset utilizado contiene información sobre facturas, productos, clientes y países donde se realizaron las ventas.

Columnas principales:

InvoiceNo: Número de factura.
StockCode: Código del producto.
Description: Descripción del producto.
Quantity: Cantidad vendida.
InvoiceDate: Fecha de la factura.
UnitPrice: Precio unitario.
CustomerID: ID del cliente.
Country: País de la compra.
Nota: El dataset original tiene algunos valores nulos en las columnas Description y CustomerID, que fueron limpiados para el análisis.

Requisitos
Asegúrate de tener instalado lo siguiente antes de ejecutar el proyecto:

Python 3.8 o superior.
Librerías necesarias (instalar con pip install -r requirements.txt):
pandas
numpy
matplotlib
seaborn
Ejecución del Proyecto
Clona este repositorio en tu máquina local:
bash
Copiar código
git clone https://github.com/tu_usuario/online-retail-analysis.git
cd online-retail-analysis
Instala las dependencias:
bash
Copiar código
pip install -r requirements.txt
Descarga el dataset y colócalo en el directorio raíz del proyecto.
Ejecuta el script principal:
bash
Copiar código
python main.py
Análisis Realizado
Algunas preguntas respondidas durante el análisis incluyen:

¿Cuáles son los productos más vendidos?
¿Qué países generan más ingresos?
¿Cómo varían las ventas por mes y año?
¿Qué clientes generan más ingresos?
¿Cuál es el ticket promedio por cliente?
Resultados Clave
Top Países por Ventas: El Reino Unido lidera en cantidad y valor de ventas.
Top Productos: Identificamos los 10 productos más vendidos.
Caída en Diciembre 2011: Descubrimos que solo hubo datos disponibles para los primeros 9 días de diciembre, lo que explica una caída significativa en las ventas.
Ventas Promedio por Producto: Calculamos la cantidad promedio vendida y el ingreso por producto.
Visualizaciones
Ventas por País

Productos Más Vendidos

Ventas por Mes y Año
