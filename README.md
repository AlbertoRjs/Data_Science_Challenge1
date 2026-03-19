# 📊 Alura Store Latam - Análisis de Tiendas

## 🏆 Contexto del Desafío

Este proyecto fue desarrollado como parte del **Challenge 1 de Data Science de Alura Latam**, en colaboración con Oracle Next Education (ONE). El objetivo es aplicar técnicas de análisis de datos para resolver un problema de negocio simulado.

## 🎯 Objetivo del Proyecto

Analizar los datos de ventas, productos, calificaciones y envíos de cuatro tiendas online ficticias (Tienda 1 a Tienda 4) proporcionadas por Alura Latam. El propósito final es determinar cuál de estas tiendas representa la **mejor oportunidad estratégica** para que el "Sr. Juan" (representando al usuario o stakeholder) enfoque sus esfuerzos de venta, basándose en un análisis comparativo de su desempeño.

## 💾 Fuente de Datos

Los datos utilizados provienen de cuatro archivos CSV, cada uno representando una tienda diferente:
*   `tienda_1 .csv`
*   `tienda_2.csv`
*   `tienda_3.csv`
*   `tienda_4.csv`

Estos archivos fueron proporcionados por Alura Latam para el desafío y contienen información sobre transacciones, incluyendo detalles del producto, precios, costos de envío, fechas, calificaciones de clientes y ubicaciones geográficas.

## 🛠️ Herramientas Utilizadas

El análisis se realizó utilizando Python y las siguientes bibliotecas principales:
*   🐍 **Python 3.x**
*   🐼 **Pandas:** Para la manipulación, limpieza y agregación de datos.
*   📊 **Matplotlib & Seaborn:** Para la creación de visualizaciones y gráficos comparativos.
*   📓 **Jupyter Notebook:** Como entorno interactivo para el desarrollo del análisis y la documentación del proceso (`AluraStoreLatam.ipynb`).

## ℹ️ Descripción

Antes de pasar a análisis detallados, es esencial explorar el conjunto de datos para comprender su estructura y contenido. Este paso le permite identificar patrones, inconsistencias y las columnas más relevantes para los siguientes pasos.

Estructura de datos:
El conjunto de datos incluye la siguiente información:

*  **Producto y Categoría:** Artículos vendidos y sus calificaciones.

*  **Precio y Envío:** Valores de venta y costos asociados.

*  **Fecha y ubicación de compra:** Información temporal y geográfica.

*   **Evaluación de compra:** Comentarios de clientes.

*   **Tipo de Pago y Cuotas:** Métodos utilizados por los clientes.

*   **Coordenadas Geográficas:** Ubicación de las transacciones.

💡¡Explorar y comprender bien estos datos es el primer paso hacia un análisis eficiente!
## 📈 Resumen del Análisis Realizado

Se llevaron a cabo los siguientes análisis comparativos entre las cuatro tiendas:

1.  **💰 Ingresos Totales:** Comparación de la facturación total generada por cada tienda.
2.  **🏷️ Ventas por Categoría:** Análisis de la cantidad de productos vendidos por categoría, identificando las más y menos populares en cada tienda.
3.  **⭐ Calificación Promedio:** Calculo y comparación de la satisfacción promedio de los clientes basada en sus calificaciones.
4.  **📦 Productos Más/Menos Vendidos:** Identificación de los productos específicos con mayor y menor volumen de ventas (unidades) en cada tienda.
5.  **🚚 Costo de Envío Promedio:** Comparación del gasto promedio en envíos por transacción para cada tienda.3
## 💡 Hallazgos Clave y Visualizaciones

El análisis revelde las tiendas:

*   **Tienda 1:** Lidera en ingresos totales pero tiene la calificación promedio más baja y los costos de envío más altos.
*   **Tienda 2:** Rendimiento sólido y equilibrado, muy cercano a Tienda 3.
*   **Tienda 3:** Destaca por la **mayor satisfacción del cliente** (calificación promedio más alta) y un fuerte volumen de ventas en la categoría principal ("Muebles"), con costos de envío competitivos.
*   **Tienda 4:** Ofrece los costos de envío más bajos pero tiene los ingresos totales más bajos.

Se generaron diversos gráficos (barras, dispersión, pastel) para visualizar estas comparaciones, incluyendo:
*   Ventas totales por tienda.
*   Calificación promedio por tienda.
*   Distribución de categorías (ejemplo Tienda 1).
*   Relación Precio vs. Costo de Envío.
*   Distribución geográfica de las ventas.

## ✅ Conclusión y Recomendación

Basado en la combinación de factores (alta satisfacción del cliente, fuerte desempeño en categorías clave, ingresos sólidos y costos de envío razonables), se concluyó que la **Tienda 3** representa la **oportunidad estratégica más equilibrada y prometedora** para el Sr. Juan.

