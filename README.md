# 📊 Proyecto 5. Análisis de Planes Telefónicos | Megaline

## 🎯 Objetivo
Analizar el comportamiento de los usuarios y los ingresos generados por los planes Surf y Ultimate de la empresa Megaline, con el fin de identificar diferencias de consumo, rentabilidad y oportunidades de optimización comercial.

---

## 🛠️ Metodología y Proceso
- Limpieza, transformación y tipificación de datos con Python (pandas, numpy).
- Enriquecimiento de datasets (llamadas, mensajes, internet, usuarios y planes).
- Agregación mensual por usuario mediante groupby y merge, construyendo un dataset consolidado.
- Cálculo detallado de consumos, excedentes y ingresos mensuales por usuario.
- Análisis exploratorio con estadísticas descriptivas y visualizaciones.
- Pruebas de hipótesis con t-test de Student para validar diferencias significativas.

---

## 📈 Análisis Clave
- El consumo promedio de minutos y datos es similar entre ambos planes, aunque:
  - Los usuarios del plan Surf presentan mayor cantidad de valores atípicos.
  - Los usuarios de Surf exceden con mayor frecuencia los límites incluidos.
- El plan Ultimate muestra un comportamiento de consumo más estable.
- El análisis por región evidenció diferencias significativas entre NY–NJ y otras áreas.

--- 

## 💰 Resultados de Negocio
- Los ingresos promedio del plan Ultimate son mayores, pero más estables.
- El plan Surf, aunque más económico, genera más ingresos totales debido a:
- Mayor número de usuarios.
- Mayor frecuencia de cargos por excedentes.
- Las pruebas estadísticas confirmaron diferencias significativas:
- Entre los ingresos de Surf vs Ultimate.
- Entre los ingresos del área NY–NJ vs otras regiones.

--- 

## ✅ Conclusión
El plan Surf es el más rentable para Megaline por volumen y cargos adicionales, aunque existe una oportunidad clara de migración de usuarios intensivos hacia el plan Ultimate, lo que podría mejorar la experiencia del cliente y optimizar la estrategia comercial.

--- 

## 🧰 Herramientas
- Python 
- Pandas 
- NumPy 
- Matplotlib 
- Seaborn 
- SciPy
