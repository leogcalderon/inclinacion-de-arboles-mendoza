# inclinacion-de-arboles-mendoza


![Optional Text](https://cdn.lavoz.com.ar/sites/default/files/styles/width_1072/public/galeria_multimedia/Mendoza_1.jpeg)
¿Se puede predecir el grado de peligrosidad de una árbol dado sus características?

La Secretaría de Ambiente y Desarrollo Sustentable de la Ciudad de Mendoza Argentina, destaca a la cultura del árbol tanto como patrimonio cultural y como un aliado indispensable del progreso y el desarrollo de la vida en la provincia de Mendoza. Sin embargo, todos sabemos del peligro que suponen los arboles durante las temporadas de fuertes tormentas y sobre todo la época de viento Zonda. El grado de inclinación de un árbol es un factor fundamental a tener en cuenta a la hora de prevenir los posibles accidentes ocasionados por los fenómenos meteorológicos severos a los que muchas veces esta sujeta la provincia de Mendoza.

El objetivo detras del presente desafio es el de predecir aquellos especimenes que tengan un grado de inclinación peligroso (i.e. mayor a 30 grados) a partir de sus caracteristcas biologicas e información geografica/administrativa. Para tal fin se cuenta con un conjunto de datos que contiene el censo georeferenciado del arbolado publico en la ciudad de Mendoza al año 2012.

Los datos fueron generados a partir del Censo digital georeferenciado del arbolado público de la Ciudad de Mendoza, realizado en el año 2012. Mediante el mismo se permitió registrar de cada forestal una serie de datos que permiten definir su ubicación de un modo más preciso, actualizar la información en forma permanente y, sobre todo, planificar acciones futuras. El archivo original forma parte del del programa de Datos Abierto de la Ciudad de Mendoza.

## INDICE
1. Análisis exploratorio de datos
    1. Variables categóricas
        1. especie
        2. ultima_modificacion
        3. altura
        4. diametro_tronco
        5. nombre_seccion - area_seccion - seccion
    2. Variables numéricas
        1. circ_tronco_cm
    3. Variables geo
        1. Mapa de calor de mediciones
        2. Secciones de mediciones
2. Preprocessing
    1. One hot encoding
    2. Scaler
    3. Train/Test split
3. Modelo
    1. Sin under/over sampling / AUC Baseline
    2. SMOTE (oversampling)
        1. CV wrong way
        2. CV right way
        3. Hiperparametros
        4. Interpretación del modelo
        5. Posibles mejoras
4. Submission
