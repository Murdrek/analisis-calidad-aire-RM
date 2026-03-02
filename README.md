# Análisis de Calidad del Aire - Región Metropolitana

Este proyecto analiza datos de calidad del aire (PM2.5, PM10 y otros contaminantes) en distintas comunas de Santiago, Chile.

## Objetivos
- Integrar datos de múltiples archivos CSV en un único DataFrame.
- Normalizar y limpiar las columnas para un análisis consistente.
- Calcular promedios de contaminantes por comuna.
- Visualizar comparativamente los resultados mediante gráficos.
- Identificar comunas fuera de norma según estándares nacionales e internacionales.

## Resultados principales
- La comuna con mayor concentración promedio de **PM2.5** es **Cerro Navia** (82.10 µg/m³).
- La comuna con menor concentración promedio de **PM2.5** es **Puente Alto** (72.31 µg/m³).
- Todas las comunas superan la **norma chilena (25 µg/m³)** y la **norma OMS (5 µg/m³)**.

## Observaciones
- Se detectaron valores faltantes en algunas comunas (ej. Cerrillos carece de datos para O₃, NO₂, SO₂ y CO).
- Las diferencias más marcadas aparecen en gases como NO₂ y SO₂.

## Preguntas de negocio y respuestas con datos
<img width="498" height="654" alt="image" src="https://github.com/user-attachments/assets/c1d89d5b-c302-40c4-b8ca-b02bab0484d1" />

## Visualizaciones
El repositorio incluye gráficos comparativos que muestran:
- Concentraciones promedio de PM2.5 por comuna.
- Líneas de referencia con normas nacionales e internacionales.

## Conclusión
El análisis evidencia que la Región Metropolitana enfrenta un problema estructural de contaminación por material particulado fino.  
Esto refuerza la necesidad de políticas públicas sostenidas, cumplimiento estricto y horizontes de largo plazo para lograr mejoras significativas en la calidad del aire.

## Próximos pasos 
- Integrar datos meteorológicos (temperatura, viento, humedad) para enriquecer el análisis.
- Aplicar modelos predictivos de series temporales (ARIMA, Prophet).
- Comparar resultados con otras ciudades de Chile o Latinoamérica.
- Evaluar impacto de políticas públicas recientes en la reducción de contaminantes.

## Cómo ejecutar
1. Clonar el repositorio.
2. Instalar dependencias: `pip install pandas matplotlib`.
3. Ejecutar el notebook `Analisis_PM25_RM.ipynb`.
