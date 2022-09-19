# Momento de Retroalimentación Módulo 2
## Portafolio Implementación
Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución.
### Jorge Chávez Badillo A01749448

### Librerías Utilizadas:

* *graphviz* Software de dibujo de diagramas, en este caso utilizada para el árbol de decisión. 
* *numpy* Librería para el cálculo numérico y análisis de datos.
* *pandas* Librería para la manipulación y tratamiento de datos. 
* *seaborn* Para la visualización de datos. 
* *sklearn.tree* Módulo de sklearn para el entrenamiento de árboles de decisión. 
* *sklearn.metrics* Funciones de pérdida, puntiación y utilidad para medir el rendimiento de los modelos de clasificación. 
* *matplotlib.pyplot* Utilizada para la creación de gráficos en dos dimensiones. 
* *sklearn.tree.DecisionTreeClassifier* Para la modelación y congiguración de parámetros de los árboles de decisión. 
* *sklearn.preprocessing.StandardScaler* Librería para la estandarización de datos. 
* *mlxtend.plotting.plot_learning_curves* Utilizada para observar gráficos de desempeño de los modelos. 
* *sklearn.model_selection.train_test_split* Para la división de un dataset en dos bloques, destinados al entrenamiento y validación del modelo. 

### Dataset Utilizado

Breast Cancer, obtenido de: [dataset](https://goo.gl/U2Uwz2) y [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html#sklearn.datasets.load_breast_cancer)

### Métricas de Desempeño 

Para este modelo se realizaron 5 configuraciones de árboles de decisión, con el propósito de encontrar con que parámetros se obtenía un mayor número de score, y que por ende, se obtuvieran mejores predicciones. Los árboles obtenidos y sus scores fueron los siguientes. 

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/metricasArbolesCode.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/metricasArboles.png" width="250px">
</p>

Los siguientes son los valores de las métricas obtenidas al encontrar los mejores parámetros y valor de alpha para el modelo, en este caso el árbol final utilizado obtiene valores muy bien ajustados y en las siguientes imágenes también se pueden observar las predicciones realizadas con este modelo, los valores de entrada y una comparación entre los valores reales y la predicción obtenida. 

**Predicciones**

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/valores.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/tablaComparativa1.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/tablaComparativa2.png" width="500px">
</p>

**Métricas Obtenidas**

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/scoreArbolFinal.png" width="250px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/busquedaDeAlpha.png" width="400px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/metricasArbolFinal.png" width="350px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/classificationReport.png" width="350px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2-framework/blob/main/Imagenes/matrizConfusion.png" width="500px">
</p>

### Archivo a Revisar 
                                                                                                                             
Para una mejor visualización del programa y sus resultados, se encuentra el archivo *momentoDeRetroalimentacionM2Framework.ipynb* y de igual forma se encuentra el archivo para correr directamente en un compilador el archivo *momentoDeRetroalimentacionM2Framework.py*
