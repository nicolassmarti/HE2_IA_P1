# Predicción de aprobación de credito

¡Bienvenido a al *Proyecto de Predicción de Aceptación de Crédito*!  
Este proyecto, desarrollado por *Chigüiros Consulting Group (CCB), utiliza modelos de **Machine Learning* para predecir la aceptación o rechazo de solicitudes de crédito. Nuestro  objetivo es optimizar la evaluación de riesgos para *CTBC Bank*, mejorando la eficiencia y precisión en la aprobación de préstamos.





# Indice

- [Descripción](url)
- [Instalación de librerias](url)
- [Objetivos](url)
- [Relación economica](url)
- [Modelos](# Modelos)

# Descripción

# Instalación de librerias


- !pip install -q pandas
- !pip install -q numpy
- !pip install -q scipy
- !pip install -q matplotlib
- !pip install -q seaborn
- !pip install -q plotly
- !pip install -q yellowbrick
- !pip install -q scikit-learn
- !pip install -q imbalanced-learn
- !pip install -q tqdm
- !pip install -q joblib
- !pip install -q huggingface_hub
- !pip install -q datasets
- !pip install -q fsspec==2024.10.0

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

