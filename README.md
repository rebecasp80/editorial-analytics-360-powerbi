# 📚 Editorial Analytics 360° – Business Intelligence con Power BI

Proyecto de **Inteligencia de Negocio** aplicado al sector editorial, utilizando **Power BI**, **Power Query** y **DAX** para transformar datos crudos en un ecosistema analítico completo.  

El objetivo es apoyar decisiones estratégicas sobre catálogo, ventas, clientes y expansión editorial mediante dashboards interactivos y análisis avanzado.

---

## 🎯 Objetivo del Proyecto

- Integrar datos de catálogo, editoriales, temas, clientes y ventas.  

- Diseñar un **modelo estrella** profesional para análisis de negocio.  

- Aplicar **ETL con Power Query**, medidas DAX y visualizaciones avanzadas.  

- Construir un **dashboard ejecutivo 360°** con IA (forecast, key influencers, clustering).

---

## 📁 Estructura del Repositorio

editorial-analytics-360-powerbi/

├─ data/

│   ├─ clientes.csv

│   ├─ libros.csv

│   ├─ editoriales.csv

│   ├─ temas.csv

│   └─ clientes_libros.csv

├─ reports/

│   ├─ Analisis_estrategico_catalogo_editorial.pbix

│   ├─ Consultoria_estrategia_editorial_360.pbix

│   └─ Inteligencia_negocio_analisis_predictivo_editorial.pbix

├─ docs/

│   ├─ Actividad - Análisis estratégico de catálogo editorial.pdf

│   ├─ Actividad - Inteligencia de Negocio y Análisis Predictivo Editorial.pdf

│   ├─ Actividad - Consultoría de estrategia editorial 360°.pdf

│   ├─ Actividad - Guía de implementación métricas críticas.pdf

│   └─ Actividad - Ingeniería de Datos y Business Intelligence.pdf

├─ images/

│   ├─ dashboard_overview.png

│   ├─ mapa_ventas_ciudades.png

│   ├─ forecast_ventas.png

│   ├─ key_influencers.png

│   └─ treemap_editoriales.png

├─ README.md

├─ LICENSE.txt

└─ requirements.txt

---

## 🧠 Componentes Clave del Proyecto

1️⃣ Arquitectura y Modelado de Datos

Diseño de modelo en estrella con tablas de hechos y dimensiones.

Conexión de tablas de Libros, Editoriales, Temas, Clientes y Clientes_Libros.

Uso de tabla Calendario (CALENDARAUTO()) para inteligencia de tiempo.

2️⃣ ETL con Power Query

Ingesta y limpieza de los CSV: tipos de datos, duplicados, claves.

Detección de incoherencias: temas sin editorial, editoriales sin temas, temas sin autores o sin libros.

Normalización de nombres y validación de relaciones.

3️⃣ Inteligencia de Negocio y DAX

Medidas críticas:

Ventas = COUNTROWS(Clientes_Libros)

Índice de Diversidad Editorial (IDE)

Libros per Capita

% Variación de volumen usando SAMEPERIODLASTYEAR

KPIs de catálogo, autores, editoriales y fidelidad de clientes.

4️⃣ Visualización Avanzada e IA

Forecasting de ventas y volumen de libros.

Key Influencers para detectar impulsores clave de ventas.

Clustering para identificar temas saturados vs. nichos emergentes.

Mapas geográficos, treemaps, gráficos de embudo y tooltips avanzados.

Narrativa inteligente para explicar variaciones y oportunidades de negocio.

---

## 🛠️ Tecnologías Utilizadas

Power BI Desktop → Modelado, DAX y dashboards.

Power Query → ETL y limpieza de datos.

DAX → Medidas, KPIs y análisis temporal.

CSV / Excel → Fuentes de datos.

GitHub → Portafolio y documentación.

---

## 📸 Capturas de Dashboard

Las capturas principales se encuentran en la carpeta images/:

dashboard_overview.png → Vista general del panel ejecutivo.

mapa_ventas_ciudades.png → Análisis geográfico de ventas.

forecast_ventas.png → Previsión de ventas a 12 meses.

key_influencers.png → Factores que impulsan las ventas.

treemap_editoriales.png → Concentración de negocio por editorial.

---

## 💡 Conclusiones y Aprendizajes

Importancia de un modelo de datos bien diseñado para BI.

Uso de ETL real con Power Query para garantizar calidad de datos.

Aplicación de DAX para crear métricas de negocio relevantes.

Diseño de dashboards ejecutivos orientados a dirección y toma de decisiones.

Este proyecto demuestra competencias en Business Intelligence, modelado de datos y análisis estratégico aplicados al sector editorial.

---

## 👩‍💻 Autora

Proyecto desarrollado por Rebeca Soto como parte de su portafolio profesional de Business Intelligence y Análisis de Datos con Power BI.

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia MIT.

Consulta el archivo LICENSE.txt para más detalles.
