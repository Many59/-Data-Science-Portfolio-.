# -Data-Science-Portfolio-.

# 📊 Portafolio de Ciencia de Datos

¡Bienvenido! Este repositorio reúne los proyectos que he desarrollado como parte de mi formación y práctica en ciencia de datos. Cada carpeta contiene análisis, visualizaciones, modelos y documentación clara para mostrar mis habilidades técnicas y mi enfoque profesional.

---

## 📁 Proyectos incluidos

- **Análisis Exploratorio de Datos (EDA) Iris**
  
Análisis exploratorio completo del dataset iris, contiene medidas de sépalos y pétalos de tres especies de flores: Setosa, Versicolor y Virginica. 

Distribución de especies:
Se muestra que el dataset está balanceado entre las tres especies.
Se visualiza con un gráfico de barras estilizado.

Distribución de variables numéricas:
Histogramas para entender la dispersión de medidas.
Boxplots para comparar especies según longitud de sépalo y pétalo.

Análisis multivariado:
pairplot con KDE para observar cómo se separan las especies.
Se destaca que Setosa es fácilmente distinguible, mientras que Versicolor y Virginica se solapan más.

Correlaciones:
Se genera un heatmap personalizado que revela alta correlación entre petal_length y petal_width..

- **Análisis de Series Temporales**
  
Análisis exploratorio
Media móvil de 7 días para suavizar fluctuaciones.
Resampleo diario para entender el comportamiento por fecha.
Identificación de los días con mayores ventas.

Modelado predictivo
ARIMA:
Prueba de estacionariedad (ADF).
ACF y PACF para entender la estructura temporal.
auto_arima para seleccionar el mejor modelo.
Predicción de los próximos 7 días con bandas de confianza.

Prophet:
Preparación del dataset con formato ds y y.
Ajuste del modelo y visualización del forecast.


- **Detección de Fraudes**

Análisis completo de detección de fraudes con datos de transacciones bancarias

Exploración inicial
Revisión de nulos, duplicados y distribución de clases.
Visualización de montos por tipo de transacción.
Estadísticas separadas para transacciones fraudulentas y normales.

Análisis de correlaciones
Mapa de calor para entender relaciones entre variables.
Identificación de las variables más correlacionadas con el fraude.

Preprocesamiento
Escalado de Time y Amount con StandardScaler.
División estratificada en entrenamiento y prueba para mantener proporciones.

Modelado con Random Forest
Entrenamiento con ajuste de pesos por clase (class_weight='balanced').
Evaluación con: Matriz de confusión, Reporte de clasificación, Curva ROC y AUC, Curva Precision-Recall (clave en clases desbalanceadas)

Interpretabilidad
Ranking de las 15 variables más importantes.
Visualización con gráfico de barras para destacar insights.

- **Prediccion de Ventas**
  
Preprocesamiento
Eliminación de columnas irrelevantes (Alley).
Imputación de valores nulos con la media.
Codificación de variables categóricas con get_dummies.
Alineación de columnas entre train y test.

Modelado con Random Forest
Entrenamiento con 200 árboles.
Evaluación con métricas: MSE, RMSE y R².

Visualización de:
Las 10 variables más importantes.
Predicciones vs valores reales.
Distribución de errores (residuos).

Se hizo una comparación entre Regresión Lineal y Random Forest, teniendo Random Forest mejores Resultados en MSE, RMSE y R²

- **Segmentación de Clientes.**

Segmentación de clientes basada en comportamiento de compra.

Preprocesamiento
Limpieza de nulos, duplicados y devoluciones.
Eliminación de precios/cantidades negativas.
Cálculo de TotalPrice por transacción.

Cálculo de métricas RFM
Recency: días desde la última compra.
Frequency: número de compras únicas.
Monetary: total gastado por cliente.

Transformación y escalado
Aplicación de logaritmo para normalizar valores.
Escalado con StandardScaler para preparar clustering.

Segmentación con K-Means
Método del codo para determinar el número óptimo de clusters.
Entrenamiento con k=3.
Asignación de cluster a cada cliente.
Cálculo de centroides y resumen estadístico por grupo.

Visualización
Gráficos de dispersión:
Recency vs Monetary
Frequency vs Monetary

- **Red neuronal convolucional (CNN)**

clasificar imágenes de ropa usando el dataset Fashion-MNIST. 

Carga y preprocesamiento
Lectura de datos desde archivos CSV.
Normalización de píxeles y remodelado a formato (28, 28, 1).
Conversión de etiquetas y creación de tf.data.Dataset para entrenamiento eficiente.

Arquitectura del modelo
CNN con dos capas convolucionales + max pooling.
Capa densa con Dropout para evitar overfitting.
Activación softmax para clasificación multiclase.

Entrenamiento
Optimización con Adam y pérdida sparse_categorical_crossentropy.
Validación con EarlyStopping para evitar sobreentrenamiento.
Entrenamiento por 5 épocas con evaluación final.

Evaluación y visualización
Gráficos de precisión y pérdida por época.
Predicciones de ejemplo con imágenes, etiquetas reales y probabilidades.
Matriz de confusión y reporte por clase (precision, recall, F1-score).

---

## 🛠️ Tecnologías utilizadas

- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, Tensorflow)
- Visual Studio Code
- Machine Learning
- Power BI
- Jupyter Notebook

---

## 📬 Contacto

¿Te interesa colaborar o conocer más sobre mi trabajo?

- 📧 **Correo:** moreno.gdev@gmail.comm  
- 💼 **LinkedIn:** https://www.linkedin.com/in/manuel-moreno-7475a4370/

---

Gracias por visitar mi portafolio. ¡Estoy en constante aprendizaje y mejora!
