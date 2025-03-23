## Descripción
Este proyecto consiste en el análisis de datos aplicado a una empresa de venta de artículos deportivos con operaciones en tres ubicaciones: Ciudad Autónoma de Buenos Aires, Mar del Plata y Bariloche. Utiliza datos generados con [Mockaroo](https://mockaroo.com) para evaluar tendencias y patrones clave en ventas, rentabilidad y comportamiento de clientes durante los años 2022 y 2023.

El análisis se basa en datos ficticios y no representa información real de ninguna empresa.

Este proyecto fue la **entrega final del curso de Data Analytics en Coderhouse**.

## Objetivo
El objetivo principal es proporcionar insights sobre el rendimiento de la empresa a través del tablero de control y análisis de datos en Power BI. Algunos de los puntos clave incluyen:
- Evaluación de la rentabilidad por sucursal y categoría de producto.
- Análisis de tendencias de ventas y comparación interanual.
- Identificación de patrones de compra por segmento de clientes.
- Evolución del ticket promedio de compra.

## Estructura de datos
El conjunto de datos incluye 15 tablas:

### Tablas originales
- **CATEGORIES**: Categorías de productos.
- **CUSTOMERS**: Información de clientes.
- **DELIVERIES**: Tipos de envíos.
- **LOCATIONS**: Ubicaciones de sucursales y pedidos.
- **ORDERS**: Pedidos realizados.
- **ORDERS_DATES**: Fechas de los pedidos.
- **ORDERS_DETAILS**: Detalles de productos por pedido.
- **PAYMENTS**: Tipos de pagos.
- **POINTS_OF_SALE**: Puntos de venta.
- **PRODUCTS**: Productos.
- **RATINGS**: Calificaciones de los productos.
- **STAFF**: Empleados de la empresa.

### Tablas agregadas durante el análisis
- **MEDIDAS**: Métricas calculadas para análisis.
- **CALENDARIO**: Tabla de fechas para análisis temporal.
- **MEASURE_SWITCH**: Control de medidas dinámicas en Power BI.

## Tablero de Control
Se diseñó un dashboard en Power BI con las siguientes secciones:
1. **General**: Análisis de ventas, ganancias y órdenes por categoría y período.
2. **Clientes**: Comportamiento de compra segmentado por edad y frecuencia.
3. **Mapa**: Visualización geográfica del desempeño de las sucursales.


## Tecnologías utilizadas
- **Power BI**: Visualización de datos e informes interactivos.
- **DAX (Data Analysis Expressions)**: Cálculo de medidas personalizadas.
- **Mockaroo**: Generación de datos sintéticos.

## Instalación y Uso
1. Descargar y cargar los archivos de datos en Power BI.
2. Conectar las tablas y establecer relaciones según el diagrama entidad-relación disponible en la documentación.
3. Explorar el tablero de control y extraer insights para la toma de decisiones.

## Contacto
Para consultas, puedes contactarme en: [LinkedIn](https://www.linkedin.com/in/ochoaenzo/)