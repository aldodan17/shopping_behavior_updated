Análisis del Comportamiento de Compra — Shopping Behavior Dataset

📊 Proyecto de Análisis Exploratorio, Limpieza de Datos y Perfilamiento de Clientes

🧠 Descripción general del proyecto

Este proyecto analiza un dataset realista de comportamiento de compra con 3,900 clientes. El objetivo fue comprender los patrones de consumo, identificar segmentos potenciales, evaluar métricas clave de compra y preparar la base para futuros modelos predictivos.
Se realizó limpieza completa de datos, validación estructural, detección de outliers, análisis descriptivo, visualizaciones y generación de insights accionables sobre el comportamiento del cliente.

🛠️ Tecnologías utilizadas

Python
pandas
numpy
matplotlib
seaborn (si está disponible en el entorno)
scipy (para análisis estadísticos posteriores)
Jupyter Notebook
Técnicas de EDA, perfilamiento de clientes y análisis categórico.

📌 Metodología del proyecto
1️⃣ Carga y validación de datos

Importación del archivo shopping_behavior_updated.csv.
Revisión de estructura: 18 columnas, 3,900 registros.
Validación de tipos de datos y consistencia.
Verificación de valores nulos y duplicados (0 registros encontrados).

2️⃣ Limpieza y depuración

Conversión y estandarización de columnas categóricas.
Detección de outliers mediante IQR en:
Age
Purchase Amount (USD)
Review Rating
Previous Purchases
Confirmación de que los valores se encuentran dentro de rangos razonables.

3️⃣ Análisis Exploratorio (EDA)

Distribución de variables numéricas mediante histogramas y boxplots.
Análisis de relaciones entre categorías:
Género
Categoría del producto
Método de pago
Uso de descuentos y promociones
Frecuencia de compras
Temporada
Evaluación de patrones de gasto y comportamiento por segmentos.

4️⃣ Insights clave

“Clothing” es la categoría más comprada.
La mayoría de clientes son hombres.
Los descuentos y el tipo de envío muestran fuerte relación con el monto de compra.
Las puntuaciones de reseña se concentran en valores altos (satisfacción estable).
Correlaciones numéricas bajas → comportamiento impulsado por categorías más que por métricas continuas.

📈 Resultados y conclusiones

El dataset permite una comprensión robusta del comportamiento del consumidor, mostrando patrones claros que pueden ayudar a mejorar la segmentación, optimizar promociones y guiar decisiones basadas en datos. La base quedó lista para fases posteriores como modelos predictivos, clustering o análisis de retención.
