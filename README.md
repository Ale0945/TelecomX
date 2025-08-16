# Análisis de Datos – TelecomX

## Descripción del proyecto
Este proyecto realiza un análisis exploratorio de los datos contenidos en el archivo `TelecomX_Data.json`.  
El objetivo principal es analizar la evasión de clientes y generar métricas derivadas que permitan un entendimiento más detallado del comportamiento de los clientes a lo largo del tiempo.

## Alcances del análisis

### 1. Carga y limpieza de datos
- Se importó `TelecomX_Data.json` a un entorno de **Google Colab**.
- Se verificó la consistencia de los valores en el dataset.
- Se evaluó la calidad de los datos considerando:
  - Valores nulos.
  - Filas duplicadas.
  - Formatos incorrectos.

### 2. Cálculo de métricas derivadas
- Se creó la columna `Cuentas_Diarias`, obtenida dividiendo la facturación mensual por el número de días del mes correspondiente.
- Se calcularon totales y promedios relevantes para el análisis de clientes.

## Resultados principales
- Se identificó la cantidad de **evasión de clientes**.
- Se generó un **dataset enriquecido** con métricas diarias, listo para análisis avanzados o integración con dashboards.
- Se proporcionó una **base sólida para futuras visualizaciones** y reportes de KPI.

## Tecnologías utilizadas
- Python
- Pandas
- Google Colab

## Uso
1. Clonar este repositorio.
2. Abrir el notebook en Google Colab.
3. Ejecutar las celdas para reproducir el análisis.


