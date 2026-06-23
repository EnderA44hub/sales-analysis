# Sales Performance Analysis | Análisis de Rendimiento de Ventas

## English

### Objective
Analysis of sales performance for a retail company operating across 5 major US cities, using 1,000 transactions to identify top-performing products, city-level KPI tracking against annual targets, and actionable business insights.

### Tools Used
- **Python** (pandas, matplotlib, sqlite3) — data generation, analysis and visualization
- **SQL** (SQLite in-memory) — JOIN queries and KPI calculation
- **Google Colab** — development environment

### Key Findings
- **Top product:** Fashion with $52,529 in total sales
- **Lowest product:** Health & Beauty with $40,819 — only 22% below Fashion, suggesting a balanced portfolio
- **Only city above target:** Phoenix at 109.5% of annual goal (+$5,215)
- **Biggest underperformer:** New York at 85.6% of annual goal (-$7,936)
- **Key insight:** New York is the largest US city but the worst performer — signals a potential operational or pricing issue worth investigating

### Techniques Applied
- Data exploration and quality validation (nulls, data types, shape)
- GroupBy aggregations for product and city segmentation
- **SQL JOIN** — merging sales table with targets table to calculate KPI compliance
- KPI tracking: actual vs target, gap analysis, % achievement
- Conditional color coding in visualizations (green = above target, red = below)
- Business Intelligence reporting for stakeholder presentation

### Files
- `sales_analysis.ipynb` — full Python notebook with SQL, analysis and charts

### Dataset
Synthetic retail dataset generated with Python (numpy, pandas) simulating real-world sales transactions across 6 product lines and 5 US cities. Period: January — December 2024.

---

## Español

### Objetivo
Análisis del rendimiento de ventas de una empresa retail operando en 5 ciudades principales de Estados Unidos, usando 1,000 transacciones para identificar los productos más rentables, seguimiento de KPIs por ciudad contra metas anuales, e insights accionables para el negocio.

### Herramientas Utilizadas
- **Python** (pandas, matplotlib, sqlite3) — generación de datos, análisis y visualización
- **SQL** (SQLite en memoria) — queries con JOIN y cálculo de KPIs
- **Google Colab** — entorno de desarrollo

### Hallazgos Principales
- **Producto líder:** Fashion con $52,529 en ventas totales
- **Producto más bajo:** Health & Beauty con $40,819 — solo 22% menos que Fashion, indicando un portafolio equilibrado
- **Única ciudad sobre la meta:** Phoenix con 109.5% del objetivo anual (+$5,215)
- **Mayor bajo rendimiento:** New York con 85.6% del objetivo anual (-$7,936)
- **Insight clave:** New York es la ciudad más grande de EE.UU. pero la de peor rendimiento — señal de un posible problema operativo o de precios que merece investigación

### Técnicas Aplicadas
- Exploración y validación de calidad de datos (nulos, tipos de datos, dimensiones)
- Agregaciones con GroupBy para segmentación por producto y ciudad
- **SQL JOIN** — cruce de tabla de ventas con tabla de metas para calcular cumplimiento de KPIs
- Seguimiento de KPIs: real vs meta, análisis de brecha, % de cumplimiento
- Coloración condicional en visualizaciones (verde = sobre meta, rojo = bajo meta)
- Reporte de Business Intelligence para presentación a stakeholders

### Archivos
- `sales_analysis.ipynb` — notebook Python completo con SQL, análisis y gráficos

### Dataset
Dataset sintético de retail generado con Python (numpy, pandas) simulando transacciones reales de ventas en 6 líneas de producto y 5 ciudades de EE.UU. Período: Enero — Diciembre 2024.
