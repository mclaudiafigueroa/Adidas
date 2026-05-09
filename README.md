Análisis de Ventas de Adidas en EE.UU. | Power BI
Descripción
Dashboard de control desarrollado en Power BI para analizar el comportamiento de ventas de productos Adidas en Estados Unidos durante 2020 y 2021, con foco en la comparación entre zonas urbanas y rurales, segmentación por género, canal de venta y categoría de producto.
Hipótesis
Las zapatillas Adidas diseñadas para mujeres tienen mayores ventas en grandes áreas urbanas (Nueva York, Los Ángeles, Chicago) que en zonas menos urbanizadas o rurales (Billings, Manchester, Knoxville), debido a la concentración de tiendas físicas, tendencias de moda urbana y campañas de marketing específicas para entornos metropolitanos.
Herramientas utilizadas

Power BI (modelado relacional, DAX, Power Query, storytelling)
Excel (fuente de datos original)

Dataset
El dataset cuenta con 12 tablas relacionadas entre sí mediante modelo estrella:
Tabla de hechos: Ventas
Tablas de dimensiones: Productos, Categorías, Ciudades, Colores, Estados, Familias, Géneros, Regiones, Tipo de producto, Tipo de venta, Vendedor
Período analizado: 2020 – 2021
Canales de venta incluidos: Amazon, Foot Locker, Kohl's, Adidas (in-store, outlet, online)
Transformaciones realizadas en Power Query

Renombrado de columnas al español
Eliminación de filas y columnas en blanco
Creación de columnas personalizadas (ej: Total facturado = Precio por unidad × Unidades vendidas)
Creación de tabla calendario vinculada por fecha de factura

Estructura del tablero

Portada — navegación, fecha de última actualización y logo
Glosario — definición de términos técnicos y de negocio
Análisis global — indicadores principales de ventas a nivel país
Análisis por segmento — género, categoría, familia y color
Análisis geográfico — comparativa por región, estado y ciudad (urbano vs. rural)

Principales KPIs

Total de unidades vendidas
Total facturado
Margen operativo
Distribución de ventas por género
Ventas por canal (in-store / outlet / online)
Penetración por región y tipo de zona

Niveles de aplicación

Táctico: identificación de productos con mayor y menor rotación por región para optimizar stock y promociones
Estratégico: proyección de tendencias a largo plazo según canal, geografía y perfil de consumidor
