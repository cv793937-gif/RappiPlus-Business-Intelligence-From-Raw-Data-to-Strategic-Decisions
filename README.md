# 📊 RappiPlus Business Intelligence — From Raw Data to Strategic Decisions

**Python · SQL · A/B Testing · Cohorts · Funnel · BI Dashboard**

Proyecto end-to-end de Data Analytics enfocado en evaluar el desempeño del servicio de suscripción **RappiPlus**.  
El objetivo es transformar datos crudos en **insights accionables** para mejorar rentabilidad, retención y conversión.

---

## 🎯 Objetivo del proyecto

Responder preguntas clave del negocio:

- ¿Podemos confiar en los datos?
- ¿El negocio es rentable?
- ¿Dónde se pierden los usuarios?
- ¿Los usuarios regresan?
- ¿Los cambios en producto generan impacto?

Este repositorio integra **Python + SQL + BI** para construir una historia completa:  
**del dato → al insight → a la decisión**.

---

## 🗺️ Arquitectura del análisis

### 1) Data Quality (Python)
Limpieza, validación y estandarización de:
- Pedidos
- Catálogo
- Inversión de marketing

**Output:** 3 datasets limpios listos para análisis (`data_clean/`).

### 2) Rentabilidad del negocio (Python)
Cálculo de KPIs:
- Revenue
- Costos
- Margen
- Rentabilidad por país, categoría y dispositivo

### 3) Funnel de conversión (SQL)
Análisis del recorrido del usuario y detección de etapas con mayor **drop-off**.

### 4) Cohortes de retención (SQL)
Seguimiento de usuarios por fecha de alta para medir retención en el tiempo.

### 5) A/B Testing (Python)
Evaluación estadística de cambios en checkout para validar impacto en conversión.

### 6) Dashboard ejecutivo (Power BI / Tableau)
Visualización de KPIs, funnel, cohortes y resultados del experimento para toma de decisiones.

---

## 📁 Estructura del repositorio

```text
RappiPlus-Business-Intelligence/
│
├── README.md
├── data_raw/
│   ├── rappiplus_orders_raw.csv
│   ├── rappiplus_catalog.csv
│   └── rappiplus_marketing_spend.csv
├── data_clean/
│   ├── orders_clean.csv
│   ├── catalog_clean.csv
│   └── marketing_clean.csv
├── notebooks/
│   ├── 01_data_quality.ipynb
│   ├── 02_profitability_analysis.ipynb
│   ├── 03_funnel_sql.ipynb
│   ├── 04_cohorts_sql.ipynb
│   └── 05_ab_testing.ipynb
├── sql/
│   ├── funnel_analysis.sql
│   └── cohorts.sql
├── dashboard/
│   ├── powerbi.pbix
│   └── link_publico.txt
└── docs/
    ├── resumen_ejecutivo.pdf
    └── metodologia.md
```

---

## 📌 Resultados clave (ejemplo de sección para completar)

- Se detectó el mayor drop-off en etapa de checkout.
- El margen varía significativamente por categoría y país.
- Cohortes recientes muestran menor retención al mes 2.
- La variante B en checkout mejora conversión con significancia estadística (p < 0.05).  

> Reemplaza estos bullets por tus hallazgos reales con métricas concretas (% / valores).

---

## 📊 Dashboard

- Dashboard público:  
  https://drive.google.com/file/d/1MqizzhIN4DSMSqTnfYedKN00bFZCJKTM/view?usp=sharing

---

## ▶️ Cómo replicar el análisis

1. Clona este repositorio:
   ```bash
   git clone https://github.com/cv793937-gif/RappiPlus-Business-Intelligence-From-Raw-Data-to-Strategic-Decisions.git
   cd RappiPlus-Business-Intelligence-From-Raw-Data-to-Strategic-Decisions
   ```
2. Crea y activa entorno virtual (opcional recomendado).
3. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Ejecuta notebooks en orden:
   - `01_data_quality.ipynb`
   - `02_profitability_analysis.ipynb`
   - `03_funnel_sql.ipynb`
   - `04_cohorts_sql.ipynb`
   - `05_ab_testing.ipynb`
5. Revisa el dashboard en `/dashboard` o en el link público.

---

## 🧰 Tecnologías utilizadas

- **Python** (Pandas, NumPy, Matplotlib, SciPy)
- **SQL**
- **Power BI / Tableau**
- **Jupyter Notebook**
- **GitHub**

---

## 👤 Autor

Si trabajas en proyectos de analítica, growth o producto, ¡feliz de conectar!
