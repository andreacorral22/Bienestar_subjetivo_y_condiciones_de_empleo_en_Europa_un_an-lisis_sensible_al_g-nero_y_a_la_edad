Nota: Este README está disponible en español e inglés. The English version is provided below.

Español
------------------------------------------------------------------------------------
En este repositorio se encuentran las dos versiones utilizadas para el análisis de datos en Python de la European Social Survey (ESS), centrado en la relación entre las condiciones laborales y el bienestar subjetivo (Subjective Well-Being):

1. Código básico ("SWB y condiciones de empleo simple - Andrea Corral Barbero.ipynb")
Primera versión del análisis del proyecto, desarrollada de manera autónoma. Incluye:
- Limpieza y preparación de datos
- Análisis factorial confirmatorio
- Regresiones lineales con moderación por género, edad, y conjunta (género y edad a la vez)

2. Código ampliado ("SWB y condiciones de empleo complejo- Andrea Corral Barbero.ipynb")
Versión desarrollada a partir del análisis inicial ("SWB y bienestar subjetivo simple - Andrea Corral Barbero.ipynb") con asistencia de herramientas de Inteligencia Artificial para ampliar los procedimientos estadísticos, e incorpora:
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

Los datos utilizados proceden de la ronda 11 de la European Social Survey (ESS) recogidos en el 2023. El archivo original no se recoge en el repositorio pero se puede consultar y descargar en el siguiente link: https://ess.sikt.no/en/datafile/242aaa39-3bbb-40f5-98bf-bfb1ce53d8ef 

English
------------------------------------------------------------------------------------
This repository contains two versions of the Python code used to analyse data in Python from the European Social Survey (ESS), focusing on the relationship between employment conditions and subjective well-being.

1. Basic code ("SWB y condiciones de empleo simple - Andrea Corral Barbero.ipynb")
The initial version of the project analysis, developed independently. It includes:
- Data cleaning and preparation.
- Confirmatory factor analysis (CFA).
- Linear regression models examining moderation by gender, age, and both factors jointly.

2. Extended code "SWB y condiciones de empleo complejo- Andrea Corral Barbero.ipynb")
An extended version developed from the initial analysis, with the assistance of artificial intelligence tools to expand the statistical procedures. It includes:
- Weighted confirmatory factor analysis (CFA) and sensitivity analysis.
- Weighted least squares (WLS) regression.
- Country-clustered standard errors.
- Moderation analysis by gender and age.
- An ordinal logistic regression model as a supplementary analysis.

Main libraries
- pandas: data manipulation and preparation.
- numpy: numerical operations.
- semopy: structural equation modelling and confirmatory factor analysis.
- statsmodels: regression models and statistical analysis.
- scipy: complementary statistical tests and procedures.

The data come from Round 11 of the European Social Survey (ESS), collected in 2023. The original dataset is not included in this repository but can be accessed and downloaded through the following link:https://ess.sikt.no/en/datafile/242aaa39-3bbb-40f5-98bf-bfb1ce53d8ef 
