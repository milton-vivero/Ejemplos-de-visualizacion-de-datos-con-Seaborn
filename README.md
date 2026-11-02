# 🥑 Ecuador Avocado Analytics | Análisis y Visualización de Datos del Mercado de Aguacate

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Visualización-orange?style=for-the-badge)

## 📋 Descripción del proyecto

**Ecuador Avocado Analytics** es un proyecto de análisis exploratorio y visualización de datos orientado al estudio del mercado del aguacate en Ecuador.

El proyecto utiliza herramientas de Python para examinar el comportamiento de los precios, los volúmenes comercializados y las diferencias entre tipos de aguacate, mediante técnicas de análisis estadístico y visualización.

El objetivo es transformar los datos en información comprensible que permita identificar tendencias, patrones y oportunidades de análisis para el sector agrícola.

> **Nota metodológica:** La adaptación geográfica a Ecuador tiene fines educativos y analíticos. No representa estadísticas oficiales de producción, precios o comercialización agrícola del país.

## 🎯 Objetivos

- Analizar el comportamiento histórico del precio promedio del aguacate.
- Comparar los precios según el tipo de producto.
- Identificar patrones y tendencias mediante visualizaciones.
- Examinar relaciones entre variables numéricas.
- Aplicar técnicas de análisis exploratorio de datos (EDA).
- Desarrollar habilidades prácticas en Python, Pandas, Seaborn y Matplotlib.

## 🌎 Contexto geográfico

El proyecto plantea un contexto de análisis agrícola ecuatoriano, considerando zonas productoras y comerciales de distintas provincias:

| Provincia | Localidades de referencia |
|---|---|
| Imbabura | Ibarra, Pimampiro y Urcuquí |
| Pichincha | Guayllabamba y valles de Quito |
| Carchi | Mira |
| Tungurahua | Ambato |
| Azuay | Cuenca y zonas de valles cálidos |
| Loja | Zonas agrícolas de la provincia |
| Santa Elena | Zonas agrícolas de la provincia |

Estas localidades funcionan como referencias para la adaptación del ejercicio, no como una certificación del origen de cada registro.

## 🗂️ Estructura del proyecto

```text
Ecuador-Avocado-Analytics/
│
├── Data/
│   └── aguacates.csv
│
├── Images/
│   └── evolucion_precio_aguacate.png
│
├── Notebooks/
│   └── Ejemplos de visualizacion de datos con Seaborn.ipynb
│
├── README.md
└── LICENSE
```

## 📊 Variables del conjunto de datos

Las variables de referencia del proyecto son:

| Variable | Descripción |
|---|---|
| Date | Fecha del registro |
| AveragePrice | Precio promedio del aguacate |
| Total Volume | Volumen total comercializado |
| 4046 | Volumen asociado al código de producto 4046 |
| 4225 | Volumen asociado al código de producto 4225 |
| 4770 | Volumen asociado al código de producto 4770 |
| Total Bags | Total de bolsas comercializadas |
| Small Bags | Bolsas pequeñas |
| Large Bags | Bolsas grandes |
| XLarge Bags | Bolsas extragrandes |
| type | Tipo de aguacate |
| year | Año del registro |
| region | Región de referencia |

*La disponibilidad y denominación exacta de estas columnas debe coincidir con el archivo CSV utilizado en el notebook.*

## 🔬 Metodología de análisis

El proyecto contempla las siguientes etapas:

### 1. Importación y exploración de datos

- Carga del conjunto de datos mediante Pandas.
- Inspección de registros y dimensiones.
- Identificación de tipos de datos.
- Revisión de valores nulos y duplicados.
- Análisis estadístico descriptivo.

### 2. Análisis univariado

Estudio individual de las variables para conocer su distribución, frecuencia y comportamiento.

### 3. Análisis bivariado

Comparación de variables para identificar relaciones, diferencias de precios y tendencias según el tipo de aguacate.

### 4. Análisis multivariado

Evaluación conjunta de variables numéricas mediante matrices de correlación y mapas de calor.

### 5. Visualización de datos

Desarrollo de gráficos estadísticos con Seaborn y Matplotlib para facilitar la interpretación de los resultados.

## 📈 Visualización destacada: Evolución del precio promedio

Uno de los análisis principales consiste en observar la evolución temporal del precio promedio del aguacate y comparar su comportamiento entre los diferentes tipos de producto.

El gráfico utiliza:
- Líneas de tendencia temporal.
- Marcadores para identificar observaciones.
- Diferenciación visual por tipo de aguacate.
- Etiquetas y títulos descriptivos.
- Exportación en alta resolución para documentación.

### Resultado de la visualización

![Evolución del precio promedio del aguacate](Images/evolucion_precio_aguacate.png)

*El gráfico permite comparar visualmente la evolución del precio promedio según el tipo de aguacate. Las conclusiones deben establecerse a partir de los resultados obtenidos con los datos analizados.*

## 📉 Otras visualizaciones propuestas

El proyecto también contempla los siguientes análisis:

| Visualización | Objetivo |
|---|---|
| Gráfico de barras | Comparar precios promedio por región |
| Histograma | Analizar la distribución de precios |
| Boxplot | Identificar dispersión y posibles valores atípicos |
| Heatmap | Examinar correlaciones entre variables numéricas |
| Scatterplot | Explorar la relación entre precio y volumen |
| Lineplot | Analizar tendencias a través del tiempo |

## 🛠️ Tecnologías utilizadas

| Tecnología | Aplicación |
|---|---|
| Python | Lenguaje principal |
| Pandas | Manipulación y transformación de datos |
| NumPy | Operaciones numéricas |
| Matplotlib | Construcción de gráficos |
| Seaborn | Visualización estadística |
| Jupyter Notebook | Desarrollo y documentación del análisis |

## ⚙️ Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/milton-vivero/Ecuador-Avocado-Analytics.git
```

### 2. Ingresar al proyecto

```bash
cd Ecuador-Avocado-Analytics
```

### 3. Instalar las dependencias

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Ejecutar Jupyter Notebook

```bash
jupyter notebook
```

Abrir el notebook disponible en la carpeta `Notebooks/` y ejecutar las celdas en orden.

## 💼 Aplicaciones empresariales y agrícolas

Este proyecto permite practicar técnicas que pueden aplicarse a:

- Análisis de precios y comportamiento de mercados agrícolas.
- Comparación de productos y regiones comerciales.
- Identificación de tendencias de comercialización.
- Exploración de relaciones entre oferta, volumen y precio.
- Desarrollo de reportes para apoyar decisiones comerciales.

## 🚀 Aprendizajes del proyecto

- Limpieza y preparación de datos con Pandas.
- Conversión y tratamiento de variables temporales.
- Análisis exploratorio de datos.
- Construcción de visualizaciones estadísticas.
- Interpretación de tendencias y patrones.
- Documentación de proyectos de analítica con GitHub.

## 👨‍💻 Autor

**Milton Vivero**

Analítica de Datos | Business Intelligence | Python | Power BI | SQL

GitHub: [github.com/milton-vivero](https://github.com/milton-vivero)

## 📄 Licencia

Proyecto desarrollado con fines educativos y de aprendizaje. El uso y la redistribución de los datos deben respetar la licencia y las condiciones de la fuente original.

---

⭐ Si este proyecto te resulta útil, puedes visitar mi perfil de GitHub para conocer otros proyectos de análisis de datos y Business Intelligence.
