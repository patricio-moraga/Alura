Análisis de Desempeño de Tiendas
Descripción del Proyecto
Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas (tienda_1 a tienda_4) a partir de sus datos de ventas. El análisis incluye la importación y consolidación de datos, cálculo de facturación, ventas por categoría, calificaciones promedio, identificación de productos más y menos vendidos, y costos de envío. Finalmente, se proponen hallazgos clave, recomendaciones de cierre (si aplica) y medidas de mejora.

Estructura de Datos
Los datos se cargan desde cuatro archivos CSV (tienda_1.csv a tienda_4.csv), que contienen información sobre:

Producto: Nombre del producto.
Categoría del Producto: Categoría a la que pertenece el producto.
Precio: Precio del producto.
Costo de envío: Costo asociado al envío del producto.
Fecha de Compra: Fecha en que se realizó la compra.
Vendedor: Vendedor que realizó la venta.
Lugar de Compra: Ubicación geográfica de la compra.
Calificación: Calificación del cliente sobre la compra.
Método de pago: Forma de pago utilizada.
Cantidad de cuotas: Número de cuotas si aplica.
lat/lon: Coordenadas de latitud y longitud.
Todos los datos se consolidan en un único DataFrame llamado tiendas_unidas, al cual se le añade una columna Tienda para identificar la fuente original de cada registro.

Análisis Realizados
Análisis de Facturación: Cálculo del Ingreso Total (Precio + Costo de envío) y su suma por tienda.
Ventas por Categoría: Conteo de transacciones por Categoría del Producto.
Calificación Promedio: Cálculo de la Calificación promedio por tienda.
Productos Más y Menos Vendidos: Identificación de los 10 productos con mayores y menores ingresos generales, y también por cada tienda.
Envío Promedio por Tienda: Cálculo del Costo de envío promedio por tienda.
Gráfico de Barras Apiladas (Top 10 Productos por Tienda): Visualización de la contribución de los 10 productos más vendidos y una categoría 'Otros' al ingreso total de cada tienda.
Hallazgos Clave
Facturación: La Tienda 1 tiene la mayor facturación total, mientras que la Tienda 4 tiene la menor.
Ventas por Categoría: Electrónicos y Muebles son las categorías con mayores ventas, mientras que Libros y Artículos para el hogar son las de menor volumen.
Calificación Promedio: La Tienda 3 ostenta la calificación promedio más alta, y la Tienda 1 la más baja.
Productos Estrella: Productos como TV LED UHD 4K, Iphone 15 y Refrigerador son consistentes entre los más vendidos.
Productos de Bajo Rendimiento: Artículos como Cubo mágico 8x8, Cuerda para saltar y Dinosaurio Rex aparecen consistentemente entre los menos vendidos.
Costos de Envío: La Tienda 1 tiene el costo de envío promedio más alto, y la Tienda 4 el más bajo.
Recomendaciones y Próximos Pasos
Recomendación de Cierre de Tienda
Se sugiere considerar el cierre de la Tienda 4 debido a su consistente bajo rendimiento en facturación, a pesar de tener los costos de envío más bajos. Sus bajos ingresos no compensan su operación en comparación con las otras tiendas.

Medidas de Mejora Propuestas para las Tiendas Operativas
Tienda 1: Mejorar la calificación promedio y optimizar los costos de envío mediante programas de feedback, atención al cliente post-venta y negociación con transportistas. Podría explorar opciones de envío escalonadas o promociones de envío gratuito.
Tienda 2: Identificar nichos de mercado, invertir en la experiencia del cliente (CX) y optimizar costos de envío para destacar de su rendimiento intermedio.
Tienda 3: Capitalizar su alta satisfacción del cliente a través de programas de referidos, testimonios y programas de fidelización VIP. También se recomienda expandir su catálogo de manera controlada.
Estrategias Generales de Productos y Categorías
Potenciar Categorías y Productos Estrella: Enfocar campañas de marketing, bundles y asegurar stock robusto para Electrónicos, Electrodomésticos y los productos top de ventas.
Reevaluar Oferta de Baja Demanda: Realizar análisis de rentabilidad para la categoría de Libros y productos menos vendidos. Considerar estrategias de liquidación o reorientación hacia nichos más lucrativos.
Mejora Continua de la Experiencia de Compra: Personalización de recomendaciones y mejor visualización de productos.
