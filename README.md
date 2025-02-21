# Predicción de aprobación de credito

¡Bienvenido al Proyecto de Predicción de Aceptación de Crédito!

Este repositorio contiene un proyecto desarrollado por **Chigüiros Consulting Business (CCB)**, cuyo objetivo es optimizar la evaluación del riesgo crediticio para CTBC Bank mediante la implementación de modelos de Machine Learning. Se analizan datos históricos de solicitudes de crédito para predecir la aprobación o el rechazo de nuevas solicitudes, mejorando la eficiencia y precisión en el proceso de evaluación.

# Indice

- [Descripción](https://github.com/nicolassmarti/HE2_IA_P1/blob/main/README.md#descripci%C3%B3n)
- [Instalación de librerias](https://github.com/nicolassmarti/HE2_IA_P1/blob/main/README.md#instalaci%C3%B3n-de-librerias)
- [Objetivos](https://github.com/nicolassmarti/HE2_IA_P1/blob/main/README.md#objetivo)
- [Relación economica](https://github.com/nicolassmarti/HE2_IA_P1/blob/main/README.md#relaci%C3%B3n-economica)
- [Modelos](https://github.com/nicolassmarti/HE2_IA_P1/blob/main/README.md#modelos)

# Descripción
El proyecto Predicción de Aceptación de Crédito - CCB tiene como objetivo desarrollar un sistema basado en Machine Learning para mejorar la evaluación del riesgo crediticio en CTBC Bank, una institución financiera internacional. A través del análisis de datos históricos de solicitudes de crédito, implementamos modelos de aprendizaje supervisado para predecir con mayor precisión la aprobación o rechazo de nuevas solicitudes.

En la actualidad, CTBC Bank enfrenta desafíos en la optimización de su sistema de evaluación crediticia, el cual debe ser eficiente, preciso y ágil en la clasificación de perfiles de riesgo. La solución propuesta por Chigüiros Consulting Group (CCB) busca automatizar y mejorar este proceso, utilizando algoritmos avanzados que permitan una toma de decisiones informada y basada en datos.

A lo largo del proyecto, se comparan cinco modelos de Machine Learning para determinar cuál ofrece el mejor rendimiento en términos de precisión, interpretabilidad y eficiencia computacional.
# Instalación de librerias

Para ejecutar el proyecto, es necesario instalar las siguientes librerías:

```bash
pip install -q pandas
pip install -q numpy
pip install -q scipy
pip install -q matplotlib
pip install -q seaborn
pip install -q plotly
pip install -q yellowbrick
pip install -q scikit-learn
pip install -q imbalanced-learn
pip install -q tqdm
pip install -q joblib
pip install -q huggingface_hub
pip install -q datasets
pip install -q fsspec==2024.10.0
```

> **Nota:** Se recomienda utilizar un entorno virtual para evitar conflictos de dependencias.



# Objetivo

Optimizar la evaluación del riesgo crediticio: Mejorar la precisión y rapidez en la toma de decisiones al predecir el resultado de las solicitudes.

Automatizar el proceso de análisis: Reducir la intervención manual mediante la creación de un pipeline que integre desde la limpieza y preprocesamiento de datos hasta la evaluación del modelo.

Extraer insights relevantes: Identificar qué variables tienen mayor influencia en la aprobación de créditos, permitiendo ajustar las políticas de riesgo del banco.

# Relación economica

1. **Optimización del Crédito y Crecimiento Económico**: 
Facilitación del acceso al crédito: Un sistema más preciso de evaluación crediticia permite que más individuos y empresas accedan a financiamiento adecuado a su perfil de riesgo. Esto impulsa el consumo, la inversión y el crecimiento económico.
Reducción de la asimetría de información: En la economía, la asimetría de información es un problema central en los mercados financieros. Un modelo supervisado bien diseñado ayuda a mitigar este problema al evaluar con mayor precisión la capacidad de pago de los solicitantes.
2. **Eficiencia del Mercado Financiero**: 
Mejora en la asignación de recursos: Un sistema de aprobación de crédito más eficiente asegura que los fondos sean asignados a individuos y empresas con mayor probabilidad de pago, evitando pérdidas y aumentando la rentabilidad del banco.
Reducción del riesgo de incumplimiento: Al predecir de manera más efectiva qué clientes pueden incumplir sus pagos, el banco puede ajustar sus tasas de interés y políticas de préstamo, promoviendo un sistema financiero más estable.
3. **Impacto en la Política Monetaria y Financiera**: 
Efecto en la oferta monetaria: Si el banco optimiza la concesión de créditos, puede modificar su política de préstamos en respuesta a cambios en las tasas de interés fijadas por el banco central, alineándose con las estrategias de política monetaria.
Estabilidad del sistema financiero: Una mejor evaluación del riesgo crediticio reduce la probabilidad de crisis financieras derivadas de impagos masivos, lo que contribuye a la estabilidad macroeconómica.
4. **Inclusión Financiera y Desarrollo Económico**: 
Acceso al crédito para poblaciones sub-bancarizadas: Un modelo más eficiente podría reducir sesgos y permitir que más personas sin historial crediticio accedan a financiamiento.
Fomento del emprendimiento: Pequeñas y medianas empresas (PyMEs) pueden beneficiarse al obtener acceso más rápido y preciso a financiamiento, lo que impulsa la innovación y el empleo.
5. **Análisis Económico de los Datos**: 
Identificación de patrones de consumo y endeudamiento: Con el análisis de datos, se pueden identificar tendencias económicas en el uso del crédito, lo que puede ser útil para bancos, inversionistas y responsables de políticas económicas.
Segmentación del mercado financiero: La información obtenida puede ser utilizada para diseñar productos financieros más adecuados a cada segmento de la población.

# Modelos

Para garantizar una *comparación robusta*, se implementaron y evaluaron cinco modelos:  
1. *Random Forest* 🌳 – Conjunto de árboles de decisión con alta precisión e interpretabilidad.  
2. *XGBoost* 🚀 – Algoritmo de boosting que optimiza el rendimiento predictivo.  
3. *K-Nearest Neighbors (KNN)* 🔍 – Clasificación basada en la similitud con solicitantes previos.  
4. *Support Vector Classifier (SVC - SVM)* 📈 – Encuentra la frontera óptima de decisión para la clasificación.  
5. *PCA + KNN* 🔄 – Reduce la dimensionalidad antes de aplicar KNN para mayor eficiencia.

# Autores

- Nicolás Martínez
- Angela Aparicio
- Marcelo Yepes
- Andrés Ballén

