# Challengue-Analisis-de-datos
# Análisis de Ventas por Tienda

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y visualizar los datos de ventas de varias tiendas utilizando Python. Se utilizan bibliotecas como Pandas, Matplotlib y Seaborn para realizar un análisis exploratorio de los datos, así como para crear visualizaciones que muestren la distribución geográfica de las ventas.

## Datos

Los datos utilizados en este proyecto provienen de cuatro archivos CSV que contienen información sobre las ventas de diferentes tiendas. Cada archivo incluye columnas como:

- **Producto**: Nombre del producto vendido.
- **Categoría del Producto**: Categoría a la que pertenece el producto.
- **Precio**: Precio de venta del producto.
- **Costo de envío**: Costo asociado al envío del producto.
- **Fecha de Compra**: Fecha en que se realizó la compra.
- **Vendedor**: Nombre del vendedor.
- **Lugar de Compra**: Ubicación de la tienda.
- **Calificación**: Calificación del producto.
- **Cantidad de cuotas**: Número de cuotas para el pago.
- **lat**: Latitud de la ubicación de la tienda.
- **lon**: Longitud de la ubicación de la tienda.

## Importación de Datos

Se importan los datos de las cuatro tiendas desde URLs específicas. Cada archivo CSV se carga en un DataFrame de Pandas, lo que permite un fácil manejo y análisis de los datos.

## Análisis de Facturación

Se calcula el ingreso total de cada tienda sumando los precios de todos los productos vendidos. Este análisis permite identificar qué tienda genera más ingresos y cuál tiene un rendimiento inferior.

## Ventas por Categoría

Se agrupan las ventas por categoría de producto para cada tienda. Esto ayuda a entender qué categorías son más populares y cuáles generan más ingresos, lo que puede informar decisiones sobre inventario y marketing.

## Visualización Geográfica

Se generan gráficos de dispersión y mapas de calor para visualizar la distribución geográfica de las ventas. 

- **Gráfico de Dispersión**: Muestra la ubicación de las tiendas en un mapa, donde el tamaño de los puntos representa los ingresos generados. Esto permite identificar áreas con mayor actividad de ventas.
  
- **Mapa de Calor**: Representa la densidad de ventas en diferentes áreas geográficas, ayudando a visualizar patrones de compra y a identificar regiones con alto potencial de ventas.

## Resultados

Al ejecutar el análisis, se generarán visualizaciones que muestran:

- La distribución geográfica de las ventas.
- La densidad de ventas en diferentes áreas.

## Conclusiones

Este análisis permite identificar patrones en las ventas según la ubicación geográfica, lo que puede ayudar a tomar decisiones informadas sobre estrategias de marketing y distribución.

## Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.
