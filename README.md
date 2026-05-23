# RappiPlus: de datos a decisiones de negocio

Análisis end-to-end del desempeño de **RappiPlus**, una plataforma ficticia de e-commerce, desarrollado como proyecto de graduación del programa **Data Analyst de TripleTen** (marzo 2026).

El objetivo fue transformar datos en insights accionables para apoyar decisiones de negocio, siguiendo un flujo completo de análisis: desde la calidad de datos hasta la comunicación de resultados en dashboards interactivos.

---

## Herramientas

- **Python** (Pandas, NumPy) — limpieza y análisis de datos
- **SQL** (PostgreSQL) — funnel de conversión y retención por cohortes
- **Tableau** — dashboards ejecutivos
- **Estadística** — A/B testing con Z-test de proporciones

---

## Estructura del análisis

| Paso | Descripción |
|------|-------------|
| 1 | Carga y limpieza de datos (duplicados, nulos, tipos de datos) |
| 2 | Análisis de rentabilidad: revenue, costos, profit y KPIs comerciales |
| 3 | Funnel de conversión en SQL: identificación del punto de mayor abandono |
| 4 | Retención por cohortes: comportamiento de usuarios semana a semana |
| 5 | A/B testing estadístico: evaluación del impacto de un cambio en la UI del checkout |
| 6 | Dashboards interactivos en Tableau |

---

## Hallazgos principales

- **Revenue total:** USD 51.9M | **Profit:** USD 5.9M
- El mayor punto de abandono en el funnel es **begin_checkout** (13.3% de drop-off)
- La tasa de conversión final es del **80%** sobre 7,796 usuarios únicos
- La retención se mantiene estable en ~10% durante las primeras 3 semanas en todas las cohortes
- El cambio de UI evaluado en el A/B test **no mostró impacto estadísticamente significativo** (p = 0.42) — recomendación: no implementar

---

## Dashboards

- 📊 [Overview Ejecutivo](https://public.tableau.com/views/RappiPlus-Overview/OVERVIEW?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- 🔍 [Detalle / Drill-through](https://public.tableau.com/views/RappiPlus-Detalle/DETALLE?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---
