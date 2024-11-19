# Análisis Exploratorio de Datos: Online Retail Dataset

Este proyecto realiza un análisis exploratorio de datos (EDA) en el conjunto de datos de ventas minoristas en línea proporcionado. A continuación, se detalla el proceso, los análisis realizados y los insights obtenidos.

---

## Contenido
1. [Descripción del Dataset](#descripción-del-dataset)
2. [Limpieza de Datos](#limpieza-de-datos)
3. [Análisis Exploratorio (EDA)](#análisis-exploratorio-eda)
4. [Visualizaciones](#visualizaciones)
5. [Insights Principales](#insights-principales)
6. [Requisitos](#requisitos)
7. [Instrucciones de Uso](#instrucciones-de-uso)

---

## Descripción del Dataset
El dataset utilizado contiene información sobre transacciones realizadas por una tienda minorista en línea entre diciembre de 2010 y diciembre de 2011. Las columnas incluyen:
- **InvoiceNo**: Número de factura
- **StockCode**: Código del producto
- **Description**: Descripción del producto
- **Quantity**: Cantidad vendida
- **InvoiceDate**: Fecha de la transacción
- **UnitPrice**: Precio unitario
- **CustomerID**: Identificación del cliente
- **Country**: País de origen del cliente

---

## Limpieza de Datos
1. **Eliminación de valores nulos**:
   - Se eliminaron registros con `CustomerID` nulo.
2. **Creación de nuevas columnas**:
   - `TotalPrice`: Calculada como `Quantity * UnitPrice`.
   - `Year` y `Month`: Extraídas de la columna `InvoiceDate`.
3. **Filtrado de columnas**:
   - Se seleccionaron únicamente las columnas relevantes para el análisis.

---

## Análisis Exploratorio (EDA)
- **Ventas por país**:
  - Se analizaron las cantidades totales y los ingresos por país.
- **Productos más vendidos**:
  - Se identificaron los 10 productos más vendidos.
- **Tendencias temporales**:
  - Se observaron ventas por año y mes.
- **Clientes por país**:
  - Número de clientes únicos por región.
- **Promedio de ventas por producto**:
  - Cantidad promedio y precio total promedio por producto.

---

## Visualizaciones
1. **Ventas totales por país**:
   - Gráfico de barras de los países con mayores ingresos.
2. **Productos más vendidos**:
   - Gráfico de barras de los 10 productos más vendidos.
3. **Tendencias mensuales**:
   - Ventas agrupadas por mes y año.
4. **Clientes por país**:
   - Gráfico de barras de los países con mayor número de clientes únicos.

---

## Insights Principales
1. **País con mayores ventas**: 
   - El Reino Unido es el mercado principal con una cantidad significativamente mayor de ventas en comparación con otros países.
2. **Tendencia temporal**:
   - Diciembre de 2011 muestra una caída abrupta en ventas debido a que solo contiene datos de 9 días.
3. **Productos más vendidos**:
   - Productos como "TEA TIME TEA TOWELS" son los más populares, destacándose por la alta cantidad de unidades vendidas.
4. **Clientes recurrentes**:
   - La mayoría de los clientes provienen del Reino Unido, lo que sugiere que el negocio se centra en este mercado.
5. **Anomalías**:
   - Existen registros con cantidades y precios negativos, posiblemente indicando devoluciones.

---

## Requisitos
- **Librerías necesarias**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
- **Entorno de Python**:
  - Versiones 3.7 o superiores.

---

## Instrucciones de Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/online-retail-analysis.git
