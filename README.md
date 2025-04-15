# Análisis de la calidad del aire en CDMX (La Merced) - OpenAQ

Este proyecto realiza un análisis exploratorio de los niveles de contaminantes en la zona de **La Merced**, Ciudad de México, utilizando datos abiertos de la plataforma [OpenAQ](https://openaq.org/).

---

# Objetivo

Explorar, visualizar y extraer conclusiones preliminares sobre la calidad del aire, especialmente en compuestos como:

- Monóxido de Carbono (CO)
- Dióxido de Azufre (SO₂)
- Óxidos de Nitrógeno (NO, NO₂, NOₓ)
- Ozono (O₃)
- Partículas suspendidas PM10 y PM2.5

---

# Estructura

- `air_quality_CDMX_es.ipynb`: notebook con todo el análisis y visualizaciones
- `air_data_CDMX.csv`: base de datos descargada desde OpenAQ (La Merced, 1 mes)

---

# Visualizaciones

Algunos gráficos incluidos en el análisis:

![Gráfico de partículas PM10 y PM2.5](figure_example.png)

---

# Herramientas utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab

---

#  Conclusiones principales

- El contaminante con mayor presencia es el **Monóxido de Carbono (CO)**.
- Se observaron valores atípicos en compuestos como **NOₓ y SO₂**.
- Las **partículas PM2.5** presentan más variabilidad que las **PM10**, como era esperable.
- El análisis se realizó sobre datos de un solo mes para una sola estación (La Merced).

---

# Fuente de los datos

[OpenAQ Platform - La Merced, CDMX](https://openaq.org)

---

# Autor

**Mateo Chavez**  

---
