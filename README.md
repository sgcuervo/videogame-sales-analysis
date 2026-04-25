# Analisis de ventas de videojuegos 
En este proyecto se analiza el comportamiento del mercado de videojuegos a partir de datos históricos de ventas, plataformas, géneros y clasificaciones por edad, con el objetivo de identificar patrones relevantes entre distintas regiones. A través de visualizaciones exploratorias y pruebas estadísticas, se evalúa cómo factores como la región, el tipo de plataforma, el género y la clasificación ESRB influyen en el desempeño comercial y en la percepción de los usuarios, con el fin de extraer conclusiones útiles para la toma de decisiones estratégicas para futuras campañas publicitarías de la tienda online Ice.

### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

## Preguntas clave:
1. ¿Qué variables explican mayores ventas globales?
2. ¿Qué plataformas y géneros ofrecen mayor potencial de crecimiento?
3. ¿Cómo varían las preferencias por región?
4. ¿Las reseñas predicen el éxito comercial?

## Metodología
- **Preparación de datos:** Limpieza y estandarización para asegurar consistencia en el análisis de ventas, reseñas y plataformas.
- **Análisis de ventas:** Evaluación de variables clave (plataforma, género, reseñas) para identificar qué factores influyen en el éxito comercial.
- **Segmentación regional:** Comparación de preferencias en NA, EU y JP para orientar estrategias de mercado específicas.
- **Validación estadística:** Pruebas de hipótesis para confirmar diferencias significativas en calificaciones entre plataformas y géneros.

## Insights clave:
1. Éxito = consistencia, no pico. Las plataformas más rentables no son las que alcanzan mayores picos de ventas, sino aquellas que mantienen ingresos sostenidos en el tiempo.
2. El mercado no cae, se transforma. La caída de una plataforma no implica una contracción del mercado, sino una transición hacia nuevas generaciones.
3. Mercado “hit-driven” (alto riesgo). La mayoría de los juegos genera bajas ventas; el mercado depende de pocos títulos altamente exitosos.
4. La plataforma define el éxito. Un mismo juego puede tener resultados muy distintos según la plataforma debido a su base de usuarios.
5. Diferencias regionales claras (NA/EU vs JP). Norteamérica y Europa presentan mercados similares y de alto volumen, mientras que Japón es más pequeño y altamente específico en preferencias.
6. El éxito es multifactorial. El desempeño comercial depende de la interacción entre plataforma, género, región y timing, no de una sola variable.

## Recomendaciones:
1. Priorizar plataformas con base de usuarios consolidada. Enfocar lanzamientos en plataformas en fase madura para maximizar estabilidad de ingresos, en lugar de depender de plataformas nuevas con adopción incierta.
2. Alinear lanzamientos con ciclos de mercado. Planificar campañas y releases considerando transiciones entre generaciones de consolas para aprovechar picos de demanda.
3. Diversificar el portafolio de juegos. Reducir el riesgo del modelo “hit-driven” distribuyendo inversión en múltiples títulos en lugar de apostar por pocos lanzamientos.
4. Optimizar la selección de plataformas por juego. Adaptar el lanzamiento de cada título a las plataformas con mayor base activa de usuarios para maximizar ventas potenciales.
5. Implementar estrategias regionales diferenciadas.
   - NA y EU: campañas amplias enfocadas en volumen.
   - JP: estrategias específicas alineadas con preferencias locales
6. Diseñar estrategias integradas (no aisladas). Tomar decisiones considerando en conjunto plataforma, género, región y timing, en lugar de optimizar una sola variable.

## Diccionario de datos
El archivo cargado contiene un dataset con información sobre videojuegos, sus características y ventas. El dataset incluye los siguientes campos:

- `Name` — Nombre del videojuego.
- `Platform` — Plataforma para la cual se lanzó el videojuego (e.g., Wii, NES, GB).
- `Year_of_Release` — Año de lanzamiento del videojuego.
- `Genre` — Género del videojuego (e.g., Sports, Platform, Racing).
- `NA_sales` — Ventas en América del Norte (en millones de unidades).
- `EU_sales` — Ventas en Europa (en millones de unidades).
- `JP_sales` — Ventas en Japón (en millones de unidades).
- `Other_sales` — Ventas en otras regiones (en millones de unidades).
- `Critic_Score` — Puntuación promedio otorgada por críticos (escala de 0 a 100).
- `User_Score` — Puntuación promedio otorgada por usuarios (generalmente en una escala de 0 a 10, aunque puede tener valores atípicos como tbd).

