# Farmacia Díaz - Dashboard KPI

Proyecto de análisis de datos para la gestión de inventario y ventas de la Farmacia Díaz, desarrollado con PostgreSQL y Tableau.

El sistema permite almacenar, procesar y visualizar información relacionada con ventas, productos, lotes, proveedores, stock y vencimientos.

## Tecnologías utilizadas

- PostgreSQL 17
- pgAdmin 4
- Tableau Desktop
- SQL
- GitHub

## Base de datos

La base de datos `farmacia_diaz_kpi` contiene información de:

- Categorías
- Productos
- Proveedores
- Lotes
- Ventas
- Detalle de ventas
- Movimientos de inventario

También se implementaron relaciones mediante claves primarias y foráneas, índices y vistas SQL para el análisis de información.

## Vistas KPI

Se crearon las siguientes vistas:

- `vw_kpi_ventas`
- `vw_ventas_mensuales`
- `vw_productos_mas_vendidos`
- `vw_stock_critico`
- `vw_productos_por_vencer`
- `vw_valor_inventario`

## Indicadores principales

El dashboard muestra:

- Ventas Totales
- Ganancia Bruta
- Total de Ventas
- Ticket Promedio
- Ventas Mensuales
- Top 10 Productos Más Vendidos
- Productos con Stock Crítico
- Productos Próximos a Vencer
- Valor del Inventario al Costo
- Valor del Inventario a Precio de Venta

## Dashboard

El dashboard fue desarrollado en Tableau y conectado directamente a PostgreSQL.

Permite analizar visualmente el comportamiento de las ventas y apoyar la toma de decisiones relacionadas con inventario, productos y vencimientos.

## Archivos del proyecto

- `farmacia_diaz_kpi.sql`: estructura, datos, vistas e índices de PostgreSQL.
- `Farmacia_Diaz_KPI.twb`: dashboard desarrollado en Tableau.

## Autora

**Martha Gonzales Chumacero**  
Estudiante de Sistemas Informáticos
