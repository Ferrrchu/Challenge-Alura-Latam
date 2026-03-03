# 📊 Análisis de Rendimiento de Tiendas - Challenge Alura Latam
Este proyecto es una solución al Challenge de Data Science de Alura Latam. Consiste en un análisis exploratorio de datos (EDA) sobre las ventas, ingresos y logística de cuatro sucursales de una empresa (propiedad del "Sr. Juan"), con el objetivo final de emitir una recomendación basada en datos sobre qué tienda debería ser liquidada o vendida.

## 🛠️ Tecnologías Utilizadas
- Python 3
- Pandas: Para la limpieza, manipulación y agrupación de los datos (ETL básico).
- Matplotlib: Para la visualización de datos mediante gráficos de barras, gráficos circulares (pie charts) y diagramas de caja (boxplots).
- Google Colab / Jupyter Notebook: Entorno de desarrollo interactivo.

## 📂 Estructura del Análisis
El proyecto se divide en cinco etapas clave de análisis para entender la salud comercial de cada sucursal:
1. Análisis de Facturación: Cálculo de los ingresos totales por tienda y visualización de la participación de mercado de cada sucursal mediante un gráfico de torta.
2. Ventas por Categoría: Identificación de las categorías líder (Muebles, Electrónicos y Juguetes) mediante agrupaciones de datos (groupby) y gráficos de barras horizontales.
3. Calificación Promedio: Evaluación de la métrica de satisfacción del cliente para cada tienda.
4. Productos Más y Menos Vendidos: Uso de funciones personalizadas y operaciones de conteo (value_counts) para detectar los "productos estrella" y aquellos con menor tracción, manejando posibles empates en las ventas máximas/mínimas.
5. Envío Promedio por Tienda: Análisis de la distribución de los costos de logística utilizando diagramas de caja y bigotes (Boxplots) para identificar valores atípicos (outliers) y comprender la mediana real del costo de envío.

## 💡 Conclusión y Recomendación Estratégica
A partir de los datos procesados, se concluyó que el rendimiento general de la red es estable, pero la Tienda 4 presenta los indicadores más débiles (menor aporte a los ingresos totales y falta de productos estrella de gran volumen).
La recomendación final para la gerencia es desinvertir en la Tienda 4 para redirigir ese capital operativo hacia las tiendas con mejor rendimiento (Tienda 1 y Tienda 2).

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio:

```
git clone https://github.com/Ferrrchu/Challenge-Alura-Latam.git
```

2. Asegúrate de tener instaladas las librerías necesarias. Puedes instalarlas ejecutando:

```
pip install pandas matplotlib
```

3. Abre el archivo `AluraStoreLatam.ipynb` en Google Colab o Jupyter Notebook y ejecuta las celdas secuencialmente. Los datos se importan directamente desde sus URLs originales, por lo que no es necesario descargar archivos CSV locales.
