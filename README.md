# DataminingIA_Johan - Siniestros Viales Bogotá

## 1. Objetivo y Pregunta Central
* **Pregunta de análisis:** ¿Es posible predecir la gravedad de un siniestro vial en Bogotá a partir de la localidad, la clase de evento y el diseño del lugar?
* **Objetivo:** Aplicar técnicas de minería de datos (clasificación) sobre registros oficiales de movilidad para identificar patrones de riesgo vial.

## 2. Fuente de los Datos y Proceso de Limpieza
* **Dataset:** Muestra optimizada de 500 registros extraídos de la base de datos oficial de siniestros viales consolidados de Bogotá D.C. (`siniestros_viales_consolidados_bogota_dc(1).xlsx`).
* **Limpieza:** Se validaron nulos y duplicados mediante scripts en Python (Pandas), seleccionando las variables clave de ubicación y tipología del choque.

## 3. Técnicas de Minería de Datos Aplicadas
* Se implementó un algoritmo de **Clasificación mediante Árbol de Decisión** utilizando `scikit-learn` para segmentar los accidentes según su nivel de severidad.

## 4. Resultados Obtenidos y Conclusiones
* El modelo de clasificación logró predecir con una efectividad superior al 84% los niveles de gravedad de los siniestros a partir de las variables analizadas.
* La visualización generada (mapa de calor) detalla las correlaciones estadísticas entre los factores viales.

## 5. Limitaciones y Recomendaciones Futuras
* **Limitación:** El análisis predictivo se acotó a una muestra representativa de 500 eventos para optimizar el rendimiento computacional.
* **Recomendación:** Incorporar variables temporales (hora del día y condiciones climáticas) en futuras iteraciones para refinar el modelo predictivo.