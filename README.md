# Income Prediction Model

Proyecto de machine learning orientado a estimar ingresos mensuales a partir de variables financieras, crediticias y de comportamiento.

## Objetivo

Construir y comparar modelos de regresión que minimicen el error relativo, manteniendo un proceso trazable de limpieza, feature engineering, validación y optimización.

## Flujo de trabajo

1. Auditoría y limpieza de datos.
2. Análisis exploratorio.
3. Preparación de variables numéricas y categóricas.
4. Construcción de un baseline.
5. Feature engineering.
6. Comparación de modelos.
7. Validación cruzada y tuning.
8. Evaluación e interpretación del modelo seleccionado.

## Tecnologías

`Python` · `Pandas` · `NumPy` · `scikit-learn` · `CatBoost` · `XGBoost` · `Optuna`

## Hallazgos principales

- Las variables de deuda y comportamiento crediticio aportaron información predictiva relevante.
- El feature engineering mejoró el resultado frente al baseline.
- Los modelos de boosting ofrecieron mejor desempeño que las alternativas tradicionales evaluadas.

Las métricas, la comparación completa y el procedimiento de validación se encuentran en el notebook para evitar presentar resultados sin su contexto experimental.

## Contenido del repositorio

- [Notebook del proyecto](./income-prediction-model.ipynb)
- `train.csv`: conjunto utilizado para entrenamiento y validación.
- `test.csv`: conjunto reservado para predicción/evaluación según el flujo documentado.

## Resultado

![Resultado del modelo](https://github.com/user-attachments/assets/e4f54cd1-4326-40e6-9587-a8fbb967fae9)

## Limitaciones

- El modelo identifica asociaciones predictivas; no demuestra relaciones causales.
- Su uso sobre una población diferente requiere validación de estabilidad y drift.
- Para un entorno productivo se necesitarían controles de calidad, versionado de datos y monitoreo.

## Próximas mejoras

- Publicar un archivo de dependencias con versiones.
- Separar preparación, entrenamiento e inferencia en módulos.
- Incorporar una tabla resumida de métricas y un análisis formal de errores.
- Agregar un diccionario de variables y la fuente/licencia del dataset.

## Autora

**Sofía González Semper** — Data Analytics, operaciones y mejora de procesos.
