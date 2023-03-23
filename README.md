¿Cuál implementación fue mejor? 
* Nuestro modelo:
    * Davies Boudlin:  0.7454139163668938
    * Calinski Harabasz:  417860.1650717563
* Uso de librerías:
    * Davies Boudlin:  0.4837756712990533
    * Calinski Harabasz:  724537.2892558505

¿Por qué?
* La implementación que contó con un mejor desempeño fue el que hace uso de librarias puesto a que como se puede observar en las métricas de desempeño anteriores la metrica de Bouldin es menor aproximadamente por 0.26 y la metrica de Calinski es mayor por 306,677. En cuanto a estos valores, después de investigar, se encontró que entre más bajo es el valor de Boudlin el dato es mejor, lo cual es distinto para Calinskin que nos dice que entre más alto es el valor, es un mejor resultado. Podemos decir que el resultado de la librería es mejor debido a que existe menor separación entre clusters.


¿Como es que PCA mejora la calidad de los clusters?
* Este ayuda a mejorar la calidad de los clusters debido a que la reducción de los las dimensiones ayuda a la calidad de los clusters ya que reduce el efecto de las variables que no son relevantes o tienen una baja variabilidad. Por otra parte, ayudar a identificar las variables más importantes en la formación de los clusters. 
 
