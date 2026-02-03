# 🚦 Análisis de tráfico y contaminación – Proyecto TripleTen

## 🎯 Objetivo
Analizar datos de tráfico y contaminación para identificar en qué ciudades invertir en infraestructura de transporte, con el fin de aumentar la productividad y el bienestar de la población.

## 📊 Datos
**Fuente:**
- Movilidad urbana: TomTom Traffic Index (datos de tráfico).
- Economía urbana: OECD Cities (PIB per cápita, desempleo y población).

**Periodo:** 2024–2025

## 🛠️ Herramientas
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib

## 🔍 Proceso
- Crear un dataset único y limpio a partir de dos fuentes diferentes.
- Aplicar limpieza, estandarización y validación de tipos de datos.
- Filtrar y enfocar el análisis en ciudades latinoamericanas.
- Calcular indicadores agregados (por ciudad–año).
- Realizar análisis exploratorios y visuales.
- Documentar todos los pasos en Jupyter Notebook y exportar un dataset final listo para análisis.

## 📈 Hallazgos clave
- No se observa una relación lineal simple entre mayor PIB per cápita y menor congestión.
- Ciudades con PIB per cápita alto tienden a:
  - Presentar altos índices de tráfico cuando son polos económicos y laborales.
  - Tener mayor volumen de viajes diarios (commuting), lo que incrementa:
    - traffic_index_live
    - jams_delay
    - mins_delay
- **Interpretación:** Un mayor ingreso per cápita suele venir acompañado de mayor motorización, actividad económica intensa y concentración urbana, lo que puede elevar la congestión si la infraestructura no crece


## ✅ Conclusión
No existe una relación clara ni directa, algunas ciudades con PIB alto muestran niveles altos de congestión, pero otras con PIB similar presentan retrasos moderados o altos.El análisis permite identificar zonas prioritarias para intervención urbana. 
