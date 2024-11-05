<div style="text-align: center;">
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_naranja@4x.png?raw=true" alt="esquema" />
</div>


# Descripción de los Datos

## Datos BlinkIT Grocery Data

Recopila información sobre productos de supermercado, sus características, y el desempeño en ventas. La descripción de cada columna la tienes a continuación: 

1.	`Item Fat Content`: Indica el contenido de grasa del producto. Puede tomar valores como “Regular” o “Low Fat”, diferenciando entre productos con mayor y menor contenido de grasa.

2.	`Item Identifier`: Es un identificador único para cada producto, que permite diferenciar entre los distintos artículos en el inventario.

3.	`Item Type`: Clasifica el tipo de producto, agrupándolos en categorías generales, como “Fruits and Vegetables” (Frutas y Verduras), “Health and Hygiene” (Salud e Higiene), entre otros.

4.	`Outlet Establishment Year`: Indica el año en que se estableció la tienda o punto de venta específico, lo que podría ayudar a evaluar la antigüedad de cada tienda.

5.	`Outlet Identifier`: Un código único para cada tienda, que permite diferenciar entre los puntos de venta.

6.	`Outlet Location Type`: Muestra el tipo de ubicación de la tienda, categorizada por nivel, como “Tier 1”, “Tier 2”, o “Tier 3”, lo cual podría representar el tamaño o la densidad poblacional del área.

7.	`Outlet Size`: Define el tamaño de la tienda con valores como “Small” (Pequeño), “Medium” (Mediano), o “High” (Grande), lo cual puede influir en el inventario y en el volumen de ventas.

8.	`Outlet Type`: Indica el tipo de tienda, con categorías como “Supermarket Type1” o “Supermarket Type2”, que pueden diferenciar el enfoque o formato de venta.

9.	`Item Visibility`: Representa la visibilidad del producto en el punto de venta, un valor numérico que puede reflejar la prominencia del producto en la tienda.

10.	`Item Weight`: Peso del producto, medido en kilogramos, proporcionando una referencia física del artículo.

11.	`Sales`: Refleja las ventas del producto en términos monetarios, lo cual puede ser un indicador clave de su popularidad y rendimiento.

12.	`Rating`: Calificación del producto, probablemente asignada por los clientes, en una escala que refleja la satisfacción del cliente o la calidad percibida del producto.

## Datos Pisos

En este conjunto de datos tenemos información sobre propiedades residenciales y detalla varias características de los pisos o casas en venta o alquiler. Las columnas que tenemos son: 


1.	`society`: Nombre de la sociedad o residencia en la cual se encuentra el departamento, lo que ayuda a identificar la ubicación.

2.	`price`: Precio total de la propiedad, expresado en lakhs (unidad común en la India equivalente a 100,000).

3.	`price_per_sqft`: Precio por pie cuadrado, proporcionando una referencia del costo en función del tamaño.

4.	`bedRoom`: Número de habitaciones de la propiedad.

5.	`bathroom`: Número de baños en la propiedad.

6.	`balcony`: Número de balcones que tiene la propiedad.

7.	`floorNum`: Número de piso en el que se encuentra la propiedad.

8.	`facing`: Orientación de la propiedad (e.g., “West” para oeste), que puede ser un factor importante en las preferencias de los compradores.

9.	`agePossession`: Estado de antigüedad o posesión de la propiedad, como “Relatively New,” “Old Property,” o “Under Construction.”

10.	`BHK`: Número de habitaciones, hall, y cocina (habitaciones totales).

11.	`Dining Table, Washing Machine, Exhaust Fan, Chimney, Light, Sofa, Fan, Bed`: Indica si la propiedad incluye o no estos muebles y electrodomésticos, generalmente con valores binarios (0 o 1).

12.	`furnishing_type`: Nivel de amueblado de la propiedad, posiblemente codificado (e.g., “0” para sin amueblar, “1” para semi-amueblado, etc.).

13.	`area`: Área total de la propiedad en alguna unidad específica, como pies cuadrados, permitiendo comparar el tamaño.


## Datos Productos

Este conjunto de datos se centra en las ventas de productos de diferentes líneas y categorías de una tienda al por menor. Las columnas que tenemos son:

1.	`Retailer country`: País en el cual se encuentra el minorista o tienda que realizó la venta, como “United States”.

2.	`Order method type`: Método mediante el cual se realizó la orden, por ejemplo, “Fax”.

3.	`Retailer type`: Tipo de minorista o tienda, como “Outdoors Shop” (Tienda de Aire Libre).

4.	`Product line`: Línea de productos a la que pertenece el artículo vendido, como “Camping Equipment” (Equipo de Campamento).

5.	`Product type`: Tipo específico de producto dentro de la línea, por ejemplo, “Cooking Gear” (Equipo de Cocina).

6.	`Product`: Nombre específico del producto, como “TrailChef Deluxe Cook Set”.

7.	`Year`: Año en que se realizó la venta, proporcionando un contexto temporal.

8.	`Quarter`: Trimestre específico del año en que se produjo la venta, como “Q1 2012”.

9.	`Revenue`: Ingresos generados por la venta del producto en esa transacción.

10.	`Quantity`: Cantidad de unidades vendidas del producto.

11.	`Gross margin`: Margen bruto de la venta, posiblemente en formato decimal, que indica la rentabilidad de la transacción.

