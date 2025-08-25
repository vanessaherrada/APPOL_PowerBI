# APPOL - Power BI

## Introducción
Este proyecto demuestra las capacidades de **Power BI** para analizar datos de ventas globales procedentes de diferentes continentes, categorías y tipos de producto.  
El objetivo es ofrecer una vista de alto nivel —y a la vez interactiva— sobre:

- **Utilidad** y **margen** globales  
- Desempeño por **continente, país, año y trimestre**  
- Distribución de **unidades** vendidas y **tipos de producto**

## Archivo PBIX
- **`APPOL.pbix`**: contiene todas las consultas, modelo de datos y visualizaciones.  
- Compatible con **Power BI Desktop versión 2022.12** o superior.

## Fuentes de Datos
- Dataset de ejemplo simulado (CSV) incrustado en el propio PBIX:  
  - **Ventas 2017 - 2021**  
  - **Campos principales:** `Fecha`, `Continente`, `País`, `TipoProducto`, `Categoría`, `Unidades`, `Ingresos`, `Costos`, `Utilidad`  
- No se requieren conexiones externas ni credenciales: abre el archivo y ¡listo!

## Métricas Destacadas
| Métrica | Descripción |
|---------|-------------|
| **Utilidad Total** | Beneficio bruto acumulado (tarjeta verde) |
| **Margen (%)** | Utilidad ÷ Ingresos (tarjeta amarilla) |
| **Utilidad por Año y Continente** | Barras horizontales comparativas |
| **Unidades vs. Margen por Continente** | Gráfico de dona |
| **Mapa de Utilidad por País** | Burbujas geográficas |
| **Utilidad por Trimestre y Continente** | Línea temporal |
