📁 RappiPlus-Business-Intelligence/
│
├── 📄 README.md
│   ├── Introducción
│   ├── Objetivo del proyecto
│   ├── Arquitectura del análisis
│   ├── Tecnologías utilizadas (Python, SQL, Power BI/Tableau)
│   ├── Resultados clave
│   ├── Dashboard (link)
│   ├── Cómo replicar el análisis
│
├── 📁 data_raw/
│   ├── rappiplus_orders_raw.csv
│   ├── rappiplus_catalog.csv
│   ├── rappiplus_marketing_spend.csv
│
├── 📁 data_clean/
│   ├── orders_clean.csv
│   ├── catalog_clean.csv
│   ├── marketing_clean.csv
│
├── 📁 notebooks/
│   ├── 01_data_quality.ipynb
│   ├── 02_profitability_analysis.ipynb
│   ├── 03_funnel_sql.ipynb
│   ├── 04_cohorts_sql.ipynb
│   ├── 05_ab_testing.ipynb
│
├── 📁 sql/
│   ├── funnel_analysis.sql
│   ├── cohorts.sql
│
├── 📁 dashboard/
│   ├── powerbi.pbix  (o tableau.twbx)
│   ├── link_publico.txt
│
└── 📁 docs/
    ├── resumen_ejecutivo.pdf
    ├── metodología.md


    📊 RappiPlus Business Intelligence — End‑to‑End Analytics Project
Python · SQL · A/B Testing · Cohortes · Funnel · BI Dashboard
Este repositorio contiene un análisis end-to-end del desempeño del servicio de suscripción RappiPlus, desarrollado como proyecto final de Data Analytics.
El objetivo es transformar datos crudos en insights accionables que permitan evaluar rentabilidad, comportamiento de usuarios y oportunidades de mejora dentro del producto.

🎯 Objetivo del proyecto
Responder preguntas clave del negocio:

¿Podemos confiar en los datos?

¿El negocio es rentable?

¿Dónde se pierden los usuarios?

¿Los usuarios regresan?

¿Los cambios generan impacto?

¿Cómo comunicamos todo esto?

Este repositorio integra Python, SQL y Business Intelligence para construir una historia completa:
del dato → al insight → a la decisión.

🗺️ Arquitectura del análisis
1. Data Quality (Python)
Limpieza y validación de tres datasets principales:

Pedidos

Catálogo

Marketing spend

Resultado: 3 datasets limpios y listos para análisis.

2. Rentabilidad del negocio (Python)
Cálculo de KPIs:

Revenue

Costos

Margen

Rentabilidad por país, categoría y dispositivo

3. Funnel de conversión (SQL)
Análisis del recorrido del usuario dentro de la plataforma.
Identificación del mayor drop-off y puntos críticos del proceso.

4. Cohortes de retención (SQL)
Evaluación del comportamiento de usuarios en el tiempo.
Construcción de cohortes por fecha de registro y análisis de retención.

5. A/B Testing (Python)
Evaluación del impacto de cambios en la interfaz de checkout.
Prueba estadística para determinar si la variante mejora la conversión.

6. Dashboard ejecutivo (BI)
Visualización clara y accionable para toma de decisiones.
Incluye KPIs, funnel, cohortes y resultados del experimento.

🧰 Tecnologías utilizadas
Python (Pandas, NumPy, Matplotlib, SciPy)

SQL (consultas para funnel y cohortes)

Power BI / Tableau (dashboard final)

Jupyter Notebook

GitHub para control de versiones y documentación
📂 Repositorio completo:  
👉 [Aquí colocarás el link de tu GitHub]

📊 Dashboard:  
👉 (https://drive.google.com/file/d/1MqizzhIN4DSMSqTnfYedKN00bFZCJKTM/view?usp=sharing)

Si estás trabajando en proyectos de análisis, growth o producto, feliz de conectar y compartir ideas.

#DataAnalytics #SQL #Python #BusinessIntelligence #ABTesting #Cohorts #Funnel #RappiPlus #DataDriven
