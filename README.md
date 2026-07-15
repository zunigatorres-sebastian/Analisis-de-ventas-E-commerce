# Analisis-de-ventas-E-commerce

*Nota: Para conocer el informe completo revisar `Informe/Informe_E-commerce.pdf`*

### Objetivo
Analizar el histórico de ventas para identificar patrones de compra de los clientes, evaluar el desempeño de los productos y conocer el comportamiento de las ventas por región geográfica.

### Descripción
El proyecto utiliza un conjunto de datos en formato CSV extraído de [Datasets para Proyecto BI - Análisis de Ventas](https://www.kaggle.com/datasets/dataregina/datasets-para-proyecto-bi?select=clientes.csv), autora **Regina N. Molares**.
Está compuesto por cinco archivos: **categorías**, **clientes**, **métodos de pago**, **productos** y **ventas**.
Para el desarrollo del análisis se emplean dos herramientas complementarias:
•	**Microsoft Excel**: limpieza, transformación e integración de los datos mediante Power Query, además del análisis exploratorio (EDA).
•	**Microsoft Power BI**: modelado de datos, creación de medidas DAX, definición de KPIs y desarrollo de un dashboard interactivo para la visualización de los resultados.

### Análisis exploratorio de datos (EDA)
Se crea la tabla **ventas_maestra** a partir de una referencia de la tabla ventas, Mediante la función **Combinar consultas (Merge)** de Power Query
A partir de esta tabla se busca responder las siguientes preguntas de negocio:
•	¿Cómo se distribuyen las ventas por mes?
•	¿Cómo se distribuyen las ventas por región?
•	¿Qué categorías generan mayores ingresos?
•	¿Qué productos generan mayores ingresos?
•	¿Qué productos venden más unidades?
•	¿Cuáles son los métodos de pago más utilizados?
•	¿Cuál es la distribución de las ventas según su estado?

### KPIs y Medidas DAX
Con base en el análisis exploratorio, se definieron los siguientes indicadores clave para evaluar el desempeño de las ventas.
Ingresos Totales
Cantidad Total de Productos Vendidos
Ingreso promedio por venta
Precio Promedio

### Dashboard de Power BI

### Conclusiones
• **Rendimiento de ventas por región:**
La región de Buenos Aires registra el mayor rendimiento de ventas, concentrando aproximadamente el 35.73 % del total de ingresos. Este resultado evidencia una mayor participación comercial respecto a las demás regiones y sugiere la conveniencia de mantener estrategias de abastecimiento, inventario y promoción conforme con la demanda, sin descuidar el desarrollo comercial del resto de las zonas.

• **Desempeño de productos:**
La categoría Carnicería representa aproximadamente el 27.12 % de los ingresos totales, posicionándose como la categoría de mayor contribución durante el periodo analizado. Asimismo, el producto Asado destaca como el de mayor rendimiento, lo que podría reflejar una alta demanda dentro del conjunto de productos evaluados.

• **Comportamiento por estacionalidad:**
El análisis mensual muestra que las ventas mantienen un comportamiento relativamente estable, con excepción de enero, que presenta el menor nivel de ingresos. Por otra parte, marzo y junio concentran los mayores valores de ventas, mientras que diciembre también registra un incremento importante. Estos resultados sugieren la existencia de un comportamiento estacional que podría estar asociado a factores externos.

Autor
Sebastián Zúñiga.
