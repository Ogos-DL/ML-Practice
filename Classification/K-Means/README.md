## Código de clustering con KMeans

Este código implementa el algoritmo de clustering KMeans utilizando la librería `scikit-learn` en Python. Realiza la agrupación de datos y muestra la precisión del modelo. A continuación, se describe brevemente el flujo del código:

1. Importa las librerías necesarias: `KMeans` de `sklearn.cluster`, `numpy`, `pandas`, `matplotlib.pyplot` y `accuracy_score` de `sklearn.metrics`.
2. Lee los datos de clustering desde un archivo CSV y crea un DataFrame llamado `df_clustering_data`.
3. Extrae las características (coordenadas x e y) en un arreglo numpy `X`.
4. Extrae las etiquetas de clase en un arreglo numpy `Y`.
5. Grafica los datos de entrada en un scatter plot usando coordenadas x e y.
6. Crea un modelo de KMeans con 3 clusters y lo entrena usando los datos `X`.
7. Asigna los centroides de los clusters a variables individuales para facilitar la visualización.
8. Grafica los datos de entrada nuevamente y agrega los centroides de los clusters en diferentes colores.
9. Obtiene las etiquetas de cluster asignadas a cada punto de datos.
10. Vuelve a extraer las etiquetas de clase originales en un arreglo numpy `Y`.
11. Calcula la precisión del modelo comparando las etiquetas originales con las etiquetas de cluster asignadas.
12. Imprime la precisión del modelo.
