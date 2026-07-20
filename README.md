# Análisis del Sector TIC en Colombia
### Boletín Trimestral MinTIC | 2023 – 2025

En este repositorio encontrarás un análisis exploratorio del sector 
de Telecomunicaciones en Colombia, basado en datos oficiales del 
Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC). 
El proyecto cubre desde la carga y limpieza de datos hasta la construcción 
de visualizaciones interactivas, pasando por consultas SQL y conclusiones 
orientadas a la toma de decisiones.

## 📊 Dashboard Interactivo
👉 [Ver Dashboard en Power BI](https://app.powerbi.com/view?r=eyJrIjoiM2I0ODNkMjctZWJiMy00MDFiLWI2ODYtZGViZWNhMGI1YmIxIiwidCI6Ijc5ODcxZWIxLTYwOTYtNDJiZi05OGVmLWI0ZjNlNGVmODMxOCIsImMiOjR9)

---

## 🎯 Preguntas que guiaron el análisis

1. ¿Qué operador lidera el mercado móvil y cómo se distribuyen 
   las líneas por segmento (prepago/pospago)?
2. ¿Cómo evolucionó el tráfico de datos móviles por operador 
   entre 2023 y 2025?
3. ¿Qué departamentos lideran la adopción del 5G en Colombia?
4. ¿Existe relación entre el número de líneas en servicio y los 
   ingresos operacionales por operador?

---

## 🛠️ Stack tecnológico

| Herramienta | Uso |
|---|---|
| Python + Pandas | Carga, limpieza y transformación de datos |
| Matplotlib + Seaborn | Visualizaciones exploratorias |
| Jupyter Notebook | Entorno de desarrollo y documentación |
| Anaconda | Gestión del entorno virtual |
| SQL (SQLite3) | Consultas y validación de hallazgos |
| Power BI | Dashboard interactivo |
| Git + GitHub | Control de versiones |

---

## 📁 Estructura del proyecto
analisis_tic/
│
├── README.md
├── requirements.txt
│
├── data/
│ └── processed/ ← CSVs limpios listos para análisis
│
├── notebooks/
│ ├── 01_carga_y_limpieza.ipynb
│ ├── 02_exploracion_y_analisis.ipynb
│ ├── 03_conclusiones.ipynb
│ └── 04_consultas_sql.ipynb
│
└── dashboard/
└── capturas/ ← Imágenes exportadas del dashboard

---

## 📈 Hallazgos principales

**Mercado móvil:** Claro domina con más de 42 millones de líneas 
en servicio en Q4 2025, seguido de Movistar con 23.1M y Tigo con 
17.6M. El segmento prepago representa más del 70% del mercado en 
todos los operadores.

**Tráfico de datos:** Crecimiento sostenido entre 2023 y 2025. 
Claro supera los 370.000 TB en Q4 2025. Movistar muestra la 
tendencia de crecimiento más pronunciada, acercándose a los 
niveles de Tigo por primera vez en el periodo analizado.

**Cobertura 5G:** El 100% de los municipios reportados tienen 
cobertura 4G. La brecha digital actual es de 5G vs sin 5G — 
Antioquia lidera con 27 municipios con cobertura 5G, mientras 
que departamentos como Guainía, Vaupés y Vichada no registran 
ninguno.

**Ingresos:** Existe correlación positiva entre líneas en servicio 
e ingresos operacionales. Movistar genera mayor ingreso por línea 
que Tigo a pesar de tener menos abonados, lo que sugiere una base 
de clientes de mayor valor promedio.

---

## 🗂️ Fuente de datos

Ministerio de Tecnologías de la Información y las Comunicaciones  
Boletín Trimestral de las TIC — 2023, 2024 y 2025  
🔗 [colombiatic.mintic.gov.co](https://colombiatic.mintic.gov.co/679/w3-article-437023.html)

---

## 👤 Autor

**Jhonatan Smith Pérez Guerrero**  
Ingeniero de Telecomunicaciones  
📧 perezg1611@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jhonatan-smith-perez-guerrero-9689aa247/)