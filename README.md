# Dataset de Datos Ejemplos de Visualización de datos con Seabon

Este proyecto contiene un conjunto de datos histórico sobre el comercio de aguacates, con un enfoque específico en las principales ciudades y zonas productoras de aguacate en **Ecuador**.

## 📋 Descripción del Proyecto

El conjunto de datos original recopila transacciones de volumen y precio promedio de ventas de aguacate. En esta versión procesada:

## 📍 Regiones Productoras Incluidas

Las ciudades y localidades asignadas en la columna `Region` corresponden a las áreas con mayor presencia de cultivos de aguacate (variedades Hass y Fuerte/Guatemalteco) en Ecuador:

* **Imbabura:** Ibarra, Pimampiro, Urcuquí (Zona con mayor producción a escala nacional).

* **Pichincha:** Guayllabamba y Valles de Quito.

* **Carchi:** Mira.

* **Tungurahua:** Ambato.

* **Azuay:** Cuenca (zonas de valles cálidos).

* **Loja:** Loja.

* **Santa Elena:** Zonas de producción agrícola en la Costa.

## 📊 Estructura del Archivo CSV

El archivo principal `aguacates.csv` contiene las siguientes columnas:

| **Columna** | **Tipo de Dato** | **Descripción** | 
| `Fecha` | Texto / Date | Fecha del registro de ventas (formato MM/DD/YYYY). | 
| `Precio_Promedio` | Numérico | Precio promedio de venta por unidad de aguacate (USD). | 
| `Volumen_Total` | Numérico | Cantidad total de aguacates vendidos. | 
| `4046` | Numérico | Volumen total de ventas de aguacates pequeños/medianos (Código PLU 4046). | 
| `4225` | Numérico | Volumen total de ventas de aguacates grandes (Código PLU 4225). | 
| `4770` | Numérico | Volumen total de ventas de aguacates extra grandes (Código PLU 4770). | 
| `Bolsas_Totales` | Numérico | Cantidad total de bolsas vendidas. | 
| `Bolsas_Pequenas` | Numérico | Número de bolsas pequeñas vendidas. | 
| `Bolsas_Grandes` | Numérico | Número de bolsas grandes vendidas. | 
| `Bolsas_Extra_Grandes` | Numérico | Número de bolsas extra grandes vendidas. | 
| `Tipo` | Categórico | Tipo de producción (`convencional` u `organico`). | 
| `Anio` | Numérico | Año correspondiente a los datos. | 
| `Region` | Categórico | Ciudad/Zona productora en Ecuador. | 

## 🚀 Ejemplo de Uso (Python / Pandas)

Puedes cargar y analizar el archivo fácilmente con Python:

```
import pandas as pd

# Cargar el dataset
df = pd.read_csv('aguacates.csv')

# Mostrar las primeras filas
print(df.head())

# Resumen del precio promedio por región
precio_por_region = df.groupby('Region')['Precio_Promedio'].mean().reset_index()
print(precio_por_region)

```

## 🏷️ Licencia

Este dataset es de uso público para fines educativos, análisis estadístico y proyectos de ciencia de datos.
