# 📊 Análisis Comercial y de Ventas | Power BI

Dashboard interactivo desarrollado en **Power BI** para analizar el desempeño comercial de una empresa desde diferentes perspectivas: ventas, clientes, productos, vendedores, regiones y plantas.

El proyecto fue desarrollado aplicando técnicas de modelado, DAX, inteligencia de tiempo, parámetros dinámicos, seguridad e interactividad.

## 🎯 Objetivo

Construir una solución de Business Intelligence que permita transformar información comercial en indicadores y visualizaciones interactivas para facilitar el análisis y la toma de decisiones.

El dashboard permite analizar tanto el desempeño general de ventas como profundizar en dimensiones específicas del negocio y evaluar diferentes escenarios comerciales.

## 📈 Dashboard

### Resumen Ejecutivo

Vista general de los principales indicadores comerciales, incluyendo:

* Ventas totales.
* Ventas acumuladas YTD.
* Comparación contra el año anterior.
* Variación interanual.
* Promedio de días de entrega.
* Distribución de ventas según diferentes dimensiones del negocio.

<img width="1477" height="828" alt="image" src="https://github.com/user-attachments/assets/ca4533f7-edf0-4efd-a803-2293f72edb95" />

### Análisis de Ventas

Permite profundizar el análisis según diferentes dimensiones:

* Clientes.
* Productos.
* Categorías.
* Regiones.
* Plantas.
* Períodos.
* Participación sobre las ventas totales.

### Desempeño Comercial

Análisis orientado al rendimiento del equipo comercial mediante indicadores y rankings de vendedores.

Incluye métricas como:

* Ventas por vendedor.
* Ranking de vendedores.
* Venta máxima y mínima.
* Comparación del desempeño comercial.
* Análisis por planta.

### Análisis de Escenarios

Se incorporaron herramientas interactivas que permiten modificar dinámicamente el análisis.

Mediante **Field Parameters**, el usuario puede seleccionar diferentes dimensiones y métricas sin necesidad de utilizar múltiples visualizaciones.

También se implementó un **What-if Parameter** para modificar el objetivo de ventas y analizar dinámicamente qué resultados se encuentran por encima o por debajo del target establecido.

<img width="1474" height="827" alt="image" src="https://github.com/user-attachments/assets/52a9914b-eb42-4da6-afae-5bdd874f4979" />

## ⚙️ Funcionalidades implementadas

El proyecto incorpora diferentes funcionalidades de Power BI:

* Modelado de datos.
* Transformación de datos con Power Query.
* Medidas y cálculos mediante DAX.
* Time Intelligence.
* Comparaciones YTD vs. año anterior.
* Rankings dinámicos.
* Field Parameters.
* What-if Parameters.
* Bookmarks.
* Navegación mediante botones.
* Títulos dinámicos.
* Segmentadores interactivos.
* Row-Level Security (RLS).

## 🧮 DAX

Algunas de las métricas desarrolladas incluyen:

* Ventas Totales.
* Ventas YTD.
* Ventas LY.
* Variación YTD vs. LY.
* Participación sobre ventas totales.
* Ranking de vendedores.
* Venta máxima por vendedor.
* Venta mínima por vendedor.
* Promedio de días de entrega.
* Ventas sobre Target.
* Ventas bajo Target.
* Top Producto.

Estas medidas permiten modificar dinámicamente los resultados según el contexto de filtros aplicado por el usuario.

## 🔐 Row-Level Security

Se implementó **Row-Level Security (RLS)** para simular diferentes niveles de acceso a la información.
La seguridad permite restringir los datos visualizados según el usuario, demostrando la aplicación de esquemas de seguridad dentro de Power BI.

## 🧭 Navegación e interactividad

El dashboard fue diseñado buscando una experiencia de navegación similar a una aplicación.

Se utilizaron:

* Botones de navegación.
* Page Navigator.
* Bookmarks.
* Segmentadores.
* Parámetros dinámicos.
* Cambios de visualización.

La estructura permite navegar desde una visión ejecutiva hacia análisis comerciales de mayor detalle.

## 🛠️ Tecnologías utilizadas

**Power BI Desktop**
**Power Query**
**DAX**
**DAX Studio**
**Data Modeling**
**Data Visualization**
**Business Intelligence**

## 📂 Estructura del repositorio

```text
power-bi-sales-analytics/
│
├── README.md
│
├── dashboard/
│   └── NZarate_PowerBI_SalesAnalytics.pbix
│
└── images/
    ├── 01_inicio.png
    ├── 02_resumen_ejecutivo.png
    ├── 03_ventas.png
    ├── 04_desempeno_comercial.png
    ├── 05_escenarios.png
    └── 06_ventas_vs_target.png
```

## 👤 Autor

**Nicolás Zárate**

Proyecto desarrollado como trabajo final del curso **Power BI Avanzado — UTN**, 2026.
