En este repositorio se encuentran las dos versiones utilizadas para el análisis de datos en Python de la European Social Survey (ESS), centrado en la relación entre las condiciones laborales y el bienestar subjetivo (Subjective Well-Being):

1. Código básico ("SWB y bienestar subjetivo simple - Andrea Corral Barbero.ipynb")
Primera versión del análisis del proyecto, desarrollada de manera autónoma. Incluye:
- Limpieza y preparación de datos
- Análisis factorial confirmatorio
- Regresiones lineales con moderación por género, edad, y conjunta (género y edad a la vez)

2. Código ampliado ("SWB y bienestar subjetivo complejo- Andrea Corral Barbero.ipynb")
Versión desarrollada a partir del análisi inicial("SWB y bienestar subjetivo simple - Andrea Corral Barbero.ipynb"), con asistencia de herramientas de Inteligencia Artificial para ampliar los procedimientos estadísticos e incorpora:
- Análisis CFA con ponderación y análisis de sensibilidad.
- Regresión lineal ponderada (WLS).
- Errores estándar agrupados por país.
- Análisis de moderación por género y edad.
- Modelo logit ordinal como análisis complementario.

Librerías principales
- pandas: manipulación y preparación de datos.
- numpy: operaciones numéricas.
- semopy: modelos de ecuaciones estructurales y análisis factorial confirmatorio.
- statsmodels: modelos de regresión y análisis estadístico.
- scipy: pruebas y procedimientos estadísticos complementarios.

Los datos utilizados proceden de la ronda 11 de la European Social Survey (ESS) recogidos en el 2023. El archivo original no se recoge en el repositorio pero se puede consultar en el siguiente link: https://ess.sikt.no/en/datafile/242aaa39-3bbb-40f5-98bf-bfb1ce53d8ef 
