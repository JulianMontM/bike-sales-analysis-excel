# bike-sales-analysis-excel
Dashboard interactivo en Excel para analizar patrones de compra de clientes. Proyecto de demostración de limpieza de datos y segmentación lógica.
# 🚲 Análisis de Ventas de Bicicletas - Excel Dashboard

## 📌 Descripción del Proyecto
Este proyecto consiste en un análisis de datos completo (End-to-End) sobre el comportamiento de compra de bicicletas de más de 1,000 clientes.

El objetivo principal fue transformar datos crudos en insights accionables para entender qué factores demográficos (ingresos, distancia de viaje, edad, etc.) influyen más en la decisión de compra.

## 🛠️ Herramientas y Habilidades Técnicas
* **Microsoft Excel:** Herramienta principal.
* **Limpieza de Datos (ETL):** Estandarización de valores y eliminación de duplicados.
* **Lógica Condicional:** Uso de fórmulas anidadas (`SI`/`IF`) para segmentación de clientes.
* **Tablas Dinámicas:** Agrupación y resumen de datos para el análisis.
* **Visualización de Datos:** Creación de un Dashboard interactivo con Slicers (segmentación de datos).

---

## 📊 Dashboard Final
A continuación se muestra el tablero interactivo diseñado para visualizar los hallazgos clave.

<img width="950" height="606" alt="Bikes Sales Dashboard" src="https://github.com/user-attachments/assets/7e46af72-f1ca-4ceb-80bd-6d51d7351f3a" />


---

## 🔄 Proceso de Trabajo

### 1. Limpieza y Transformación de Datos
La base de datos original contenía valores abreviados y formatos inconsistentes. Se realizó un proceso de limpieza en la hoja de trabajo ("Working Sheet"):
* **Normalización:** Se reemplazaron abreviaturas como "M" y "S" por "Married" y "Single", y "F"/"M" por "Female"/"Male" para mejorar la legibilidad.
* **Clasificación de Edades:** Se creó una nueva columna `Age Bracket` utilizando fórmulas condicionales para agrupar a los clientes en "Adolescent", "Middle Age" y "Old".
* **Eliminación de Duplicados:** Se depuró la base de datos para asegurar la integridad del análisis.

*Vista de la hoja de datos limpia:*
<img width="1721" height="648" alt="Working Sheet" src="https://github.com/user-attachments/assets/5e62ccf9-3a18-4090-9401-3aadb07b4ae2" />


### 2. Análisis con Tablas Dinámicas
Se crearon tablas dinámicas para cruzar variables clave:
* Promedio de ingresos por género y decisión de compra.
* Relación entre la distancia de viaje (Commute Distance) y la compra de bicicletas.
* Análisis de compras por rango de edad.

### 3. Visualización
Se construyó un Dashboard que incluye:
* Gráficos de barras y líneas para comparar tendencias.
* **Slicers (Filtros interactivos):** Permiten filtrar todo el reporte por Región, Estado Civil y Educación con un solo clic.

---

## 💡 Conclusiones Clave (Insights)
Basado en el análisis de los datos, se observaron los siguientes patrones:
1.  **Distancia de Viaje:** Los clientes con trayectos cortos (**0-1 Millas**) son los más propensos a comprar una bicicleta. A medida que la distancia aumenta, la probabilidad de compra disminuye.
2.  **Edad:** El grupo de **"Middle Age"** representa el segmento más fuerte de compradores.
3.  **Ingresos:** Existe una correlación entre ingresos ligeramente más altos y la decisión de compra, especialmente en el segmento masculino.

---

## 📂 Estructura del Archivo
* `Excel Project Dataset.xlsx`: Archivo completo que incluye:
    * `bike_buyers`: Datos originales (Raw Data).
    * `Working Sheet`: Datos limpios y transformados.
    * `Pivot Table`: Tablas dinámicas y cálculos.
    * `Dashboard`: Visualización final interactiva.

---
*Autor: Mariano Julian Montoro - https://github.com/JulianMontM/JulianMontM*
