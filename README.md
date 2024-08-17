# K-Means
K-means es uno de los algoritmos de clustering más utilizados en Machine Learning para agrupar datos en diferentes clusters o grupos. Es un método no supervisado, lo que significa que se utiliza para encontrar patrones o estructuras en los datos sin usar etiquetas predefinidas.

Conceptos Clave de K-means
Clusters: Un cluster es un grupo de datos que son similares entre sí y diferentes de los datos en otros clusters.

Centroides: En K-means, un "centroide" es el punto que representa el centro de un cluster. Cada punto de datos se asigna al cluster cuyo centroide está más cercano.

K: El número de clusters que el algoritmo intenta encontrar. Este valor debe ser definido antes de ejecutar el algoritmo.

Funcionamiento del Algoritmo K-means
Inicialización: Se seleccionan aleatoriamente K centroides en el espacio de datos.
Asignación de Clusters: Cada punto de datos se asigna al cluster cuyo centroide está más cercano.
Actualización de Centroides: Se recalculan los centroides como la media de los puntos de datos asignados a cada cluster.
Repetición: Los pasos de asignación de clusters y actualización de centroides se repiten hasta que los centroides ya no cambian significativamente (convergencia) o se alcanza un número máximo de iteraciones.
