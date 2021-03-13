
# Deteccion y enmascaramiento de granos secciones delgadas ( V0.5)

Este projecto pretende recopilar informacion suficiente para la generacion de modelos de aprendizaje automatico para la extraccion de granos de minerales en secciones delgadas, dichos granos pueden variar en su forma , textura, tamaño , redondez entre otros, por lo cual se busca llenar al lector de conocimiento e informacion que le puedan ser util para contribuir a este projecto. 

# Data

El conjunto de datos aqui recopilado consiste en la seleccion de muestras representativas de rocas igneas, metamorficas y sedimentarias, tomadas con distintos tipos de microscopios y con distintas tecnicas, como por ejemplo luz poralizada , de las cuales a continuacion se muestran un ejemplo 

# Roca 


- Cambio del espacio de color
- Efecto de tecnicas de suavizado
- Algoritmos de deteccion de borde
- Transformaciones morfologicas sobre la imagen
- Tecnicas y patametros de umbralizados

para ello se crea un notebook de jupyter que permite evaluar el conjunto del dataSet el cual esta copuesto por los siguientes imagenes

 ### Metamorficas PPL
 Conjunto de 250 imagenes de tamaño 250*350 en formato PNG numerados de manera Ascendente con nomenclatura ./Muestra#
 ![imagen tipo1](https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/Readme/Typo1.png) 
 
 ### Igneas PPL
 Conjunto de 250 imagenes de tamaño 250*350 en formato PNG numerados de manera Ascendente con nomenclatura ./Muestra#
 ![imagen tipo1](https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/Readme/tipo2.png) 
 
 ### Sedimentarias PPL
 Conjunto de 250 imagenes de tamaño 250*350 en formato PNG numerados de manera Ascendente con nomenclatura ./Muestra#
 ![imagen tipo1](https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/Readme/tipo3.png)
  
 
 ### Metamorficas XPL
 Conjunto de 250 imagenes de tamaño 250*350 en formato PNG numerados de manera Ascendente con nomenclatura ./Muestra#
 
 ### Igneas XPL
 Conjunto de 250 imagenes de tamaño 250*350 en formato PNG numerados de manera Ascendente con nomenclatura ./Muestra#
 
 ### Sedimentarias XPL


# Requerimientos

- Python 3.6 o superior
 - opencv 3
 - matplotlib

# Instalaccion y uso

# Cambio canal de color 

El cambio de color de la imagen original se hace mediante el uso de la libreria OpenCv, especificamente se realizan los siguientes cambios de color 
 ### RGB a HSV 
 ### RGB a HSI 
 ### RGB a YCBCR
 
 # Impacto de los metodos de suavizado 
 
 El impacto que tiene el suavizado en las imagenes difiere del tipo de roca, ya que entre rocas puede haber distintas efectos, algunos positivos otros negativos, sin embargo este impacto se debe hacer en rocas igneas al ser las que pueden tener secciones laminares
 
# Analisis

Se encuentra que e el primer acercamiento con el cambio de colores, tecnicas de suavizado y umbralizado es posible optimizar la extraccion de caracteristicas de sin embargo este avance se debe complementar con la extracion semantica de la escena 

# Bibligrafia
aun Falta un poco 

# Colaborators
 - [Johan Ramírez](https://github.com/joaramirezra)
