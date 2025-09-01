# Análisis de Indicadores Demográficos y de Salud Global

Este proyecto presenta un análisis detallado de la **población mundial por área, la mortalidad infantil y la esperanza de vida por regiones**. El objetivo es identificar tendencias clave, disparidades entre continentes y la relación entre estos importantes indicadores de salud y desarrollo.

---

### Metodología del Análisis

Para este informe, se siguieron los pasos del ciclo de vida del análisis de datos utilizando **Power BI**:

1.  **Extracción, Transformación y Carga (ETL):** Los datos fueron limpiados y estructurados con **Power Query**. Las tareas clave incluyeron la gestión de valores nulos, la estandarización de los nombres de países y continentes, y la validación de los datos numéricos.
2.  **Modelado de Datos:** Se estableció un modelo de datos robusto con relaciones entre las tablas, optimizando el rendimiento para el análisis interactivo.
3.  **Análisis y DAX:** Se crearon medidas **DAX** clave para calcular métricas como la suma de población, promedios de mortalidad infantil y esperanza de vida por continente.

---

### Dashboard y Visualizaciones

El informe se divide en dos secciones principales para ofrecer una visión completa y detallada de los datos.

#### 1. Dashboard de Población por Área

<img width="890" height="480" alt="Captura de pantalla 2025-08-31 222725" src="https://github.com/user-attachments/assets/46754108-ca0c-406b-abd3-e6f9fadbe368" />

* **Población por Área:** El **Treemap** muestra claramente la distribución de la población mundial, con los países de **Asia** (especialmente China e India) dominando la proporción. Es una visualización efectiva para entender rápidamente la densidad poblacional.
* **Detalle por País:** La tabla en la parte inferior izquierda desglosa la población por cada país y su continente, permitiendo un análisis preciso y la identificación de las naciones más pobladas.

#### 2. Dashboard de Indicadores Mundiales

<img width="880" height="481" alt="Captura de pantalla 2025-08-31 222740" src="https://github.com/user-attachments/assets/9b42dfd3-b036-482d-bb62-36be2b40d24c" />

* **Análisis Geográfico:** El **mapa interactivo** visualiza la distribución de la mortalidad infantil y la esperanza de vida a nivel global, destacando áreas con mayores desafíos.
* **Relación entre Indicadores:** El gráfico de dispersión (scatter plot) muestra una clara correlación negativa: los países con una **mayor mortalidad infantil** tienden a tener una **menor esperanza de vida**, lo que resalta la importancia de la atención médica y las condiciones de vida.
* **Visión General por Continente:** La tabla y el gráfico de barras en la parte superior del dashboard permiten una comparación rápida entre continentes, confirmando que **África** enfrenta los mayores desafíos en cuanto a mortalidad infantil.

---

### Conclusiones y Recomendaciones

El análisis de estos datos revela insights críticos sobre el desarrollo global:

* **Desafíos en la Salud Global:** Existe una clara necesidad de mejorar los sistemas de salud en los continentes con alta mortalidad infantil, como África, para aumentar la esperanza de vida y mejorar el bienestar de la población.
* **Disparidades por Región:** Las diferencias en la esperanza de vida entre continentes como Europa y África son significativas. Se recomienda investigar los factores subyacentes (acceso a servicios de salud, saneamiento, educación) para comprender estas disparidades.
* **Análisis de Correlación:** La fuerte relación entre la mortalidad infantil y la esperanza de vida demuestra que las inversiones en salud materno-infantil son cruciales para el desarrollo humano a largo plazo.

---

### Archivos del Proyecto

* **`[reporte-demografico-global.pbix](https://app.powerbi.com/groups/me/reports/aad2a871-a946-4f14-a3c8-0f77b989f7aa?ctid=312d334d-75c2-4f23-80af-db347d214188&pbi_source=linkShare)`**: El archivo de Power BI con el modelo de datos y el informe interactivo.
