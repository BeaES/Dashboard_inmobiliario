# Dashboard Inmobiliario

Este repositorio contiene un **dashboard en Power BI** para el análisis de inversiones inmobiliarias.

## Contenido

- `DashboardInmobiliario.pbix` – Archivo principal de Power BI con los gráficos, tarjetas y slicers.
- `README.md` – Este archivo con información del proyecto.

## Objetivo

El dashboard permite:

- Visualizar el **beneficio total** por inmueble.  
- Calcular la **rentabilidad anual promedio** por inmueble.  
- Filtrar la información según el **número de meses de operación**.  
- Interactuar con los gráficos para ver el detalle de cada inmueble.

## Estructura de los datos

Los datos se basan en una tabla llamada `datos_inmobiliarios` con las siguientes columnas:

| Columna          | Descripción                                |
|-----------------|--------------------------------------------|
| Inmueble        | Nombre o código del inmueble               |
| Compra          | Precio de compra                            |
| Reforma         | Gastos de reforma                            |
| OtrosGastos     | Otros gastos asociados                       |
| Venta           | Precio de venta                             |
| MesesOperación  | Tiempo de operación en meses                |

## Uso

1. Abrir el archivo `.pbix` en Power BI Desktop.  
2. Seleccionar un inmueble en los gráficos para ver el beneficio y la rentabilidad correspondientes.  
3. Ajustar el **slider de meses de operación** para filtrar los resultados según el tiempo de inversión.

## Notas

- Las tarjetas muestran el **beneficio total** y la **rentabilidad anual promedio**, actualizadas automáticamente según el filtro aplicado.  
- Los gráficos incluyen etiquetas de datos al pasar el ratón por encima.  

## Autor

Proyecto creado por [Tu Nombre].
