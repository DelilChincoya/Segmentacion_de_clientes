# Segmentacion de Usuarios de Tarjetas de Crédito

![resumen de resultados](https://github.com/DelilChincoya/Segmentacion_de_clientes/blob/main/Imagenes/Segmentacion_resumen.png)

En este proyecto se realiza la segmentación de clientes con base en sus patrones de comportamiento de uso de tarjetas de crédito. La segmentación se realizó utilizando tres algoritmos distintos, y los resultados fueron analizados gráficamente.

## Conjunto de datos
El conjunto de datos utilizado contiene información de clientes de tarjetas de crédito y está disponible en [Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata).El conjunto de datos está compuesto por 17 variables que reflejan diferentes aspectos del comportamiento financiero, como:

**PURCHASES:** Total de compras realizadas.  
**CREDIT_LIMIT:** Límite de crédito del cliente.  
**PAYMENTS:** Total de pagos realizados por el cliente.  

## Objetivo
El propósito del proyecto es identificar segmentos de clientes con comportamientos similares, lo que puede ser útil para diseñar estrategias de marketing personalizadas, mitigar riesgos crediticios o identificar clientes valiosos.

## Metodología

**Análisis exploratorio y preprocesamiento de los datos:**
1. Obtención de estadísticos descriptivos de las variables.
2. Visualización de los datos mediante histogramas y boxplots.
3. Escalado de las variables usando StandardScaler.
4. Manejo de datos faltantes.
5. Reducción de la dimensionalidad con PCA.

**Algoritmos de clustering:**
1. K-means
2. DBSCAN
3. Clustering jerárquico
 
**Evaluación:**
1. Comparación de los modelos de agrupamiento a partir del coeficiente de silueta.
2. Representar de las características promedio de cada cluster mediante spider plots.

## Resultados
Los resultados mostraron que K-means y el clustering jerárquico con tres clusters produjeron resultados muy similares. Ambos modelos permitieron identificar los siguientes segmentos de clientes:

**Clientes promedio:** Comportamiento cercano a la media.  
**Clientes VIP:** Alta frecuencia de compras y gasto elevado.  
**Clientes crediticios:** Uso frecuente de avances en efectivo y pagos mínimos recurrentes.  
