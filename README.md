# Deteccion de cotornos de minerales en seccones delgadas ( V0.8)

Este projecto tiene como objetivo ayudar al lector a extraer minerales presentes en una seccion delgada (PPL o XPL) de elementos primarios ( rocas igneas, metamorficas y sedimentarias) , para ello se crea un algoritmo que permite la evaluar el impacto que tiene las siguientes caracteristicas en la definicion de bordes de mineral y la respectiva extraccion : 

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
 
 
 
 

V1.0 is intended to work on a jupyter notebook: 
 - all the functions are comented
 - Discution cells aim to help future development
 - Any academic intention must be consulted with the authors 
# Analisis

# Bibligrafia

# Colaborators
 - [Johan Ramírez](https://github.com/joaramirezra)
