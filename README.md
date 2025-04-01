# A/B Testing: Cambio de Color de CTA en Página Web

Este repositorio contiene el análisis de un experimento de A/B testing realizado para evaluar el impacto del cambio de color de los botones de llamada a la acción (CTA) en la tasa de conversión de una página web.

## Descripción del Problema

Se llevó a cabo un experimento para determinar si un cambio en el color de los CTA de azul (diseño antiguo) a naranja (diseño nuevo) influía en la tasa de conversión de la página web.

* **Grupo A (Control):** Se mostró a los usuarios el diseño antiguo con los CTA en azul.
* **Grupo B (Prueba):** Se mostró a los usuarios el diseño nuevo con los CTA en naranja.

## Hipótesis

* **Hipótesis Nula (H0):** No hay diferencia significativa en la tasa de conversión entre el diseño antiguo y el diseño nuevo.
* **Hipótesis Alternativa (H1):** La tasa de conversión es significativamente más alta en el diseño nuevo con los CTA en naranja.

## Datos

El conjunto de datos utilizado para este análisis contiene información sobre las sesiones de usuario durante el experimento. Las columnas relevantes son:

* **grupo:** Indica el grupo al que perteneció el usuario (Grupo A o Grupo B).
* **conversión:** Indica si el usuario realizó una compra durante la sesión ("Yes" o "No").

## Metodología

1.  **Preparación de Datos:**
    * Carga y limpieza del conjunto de datos.
    * Conversión de la columna "conversión" a valores numéricos (1 para "Yes", 0 para "No").
2.  **Análisis Descriptivo:**
    * Cálculo de la tasa de conversión para cada grupo.
    * Visualización de las tasas de conversión mediante gráficos de barras.
3.  **Prueba de Hipótesis:**
    * Realización de una prueba de chi-cuadrado para determinar si hay una diferencia estadísticamente significativa entre los grupos.
    * Interpretación del p-valor para evaluar la significancia de los resultados.
4.  **Conclusiones:**
    * Interpretación de los resultados de la prueba de hipótesis y respuesta a la pregunta de investigación.

## Requisitos

* Python 3.x
* Pandas
* SciPy
* Matplotlib
* Seaborn


## Resultados

Los resultados del análisis se encuentran en el notebook de Jupyter. Se incluye una interpretación del p-valor y una conclusión sobre el impacto del cambio de color en la tasa de conversión.



