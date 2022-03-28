# 3-marketing-AI
Uno de los puntos críticos para los especialistas en marketing es conocer a sus clientes e identificar sus necesidades.
Al comprender al cliente, los especialistas en marketing pueden lanzar una campaña de marketing dirigida que se adapte a necesidades específicas.
Si los datos sobre los clientes están disponibles, la ciencia de datos se puede aplicar para realizar la segmentación del mercado.
En este caso práctico, nos han contratado como expertos en data science para una empresa de minorista de análisis de Seattle, U.S.
La empresa tiene muchos datos de sus clientes de los últimos 2 años y medio.
Se nos encomienda la tarea de crear campañas de marketing enfocadas a los clientes, dividiéndolos para ello en por lo menos 3 segmentos diferentes.

metodologia a seguir: 

1. entender claramente el problema.
2 entender los datos, a partir de un análisis exploratorio de datos, para ver si todas las variables nos interesan o si hay algunas mas relevantes, o si hay tendencias 
3 pre-procesar los datos, para que nuestro modelo de ML los pueda procesar 
4 esarrollar varios modelos preliminares, explorar entre varios modelos 
5 escoger el mejor modelo 


herramientas qeu usaremos:
aprendizaje no supervisado (haremos segmentación o clusterización de datos no etiquetados) K MEANS + método del codo (encontrar el número de clusters óptimo para dividir nuestros clientes) + autoencoders + ACP (PCA, modelos para datasets sin etiquetas). reducción de dimensión (para hacer visualización 3d de clusters)

Usaremos tensorflow.keras para la construccion del autoencoder, plotly, seaborn, matplotlib para la graficacion, y pandas + numpy para el analisis exploratorio de datos y limpieza de los mismos. 
