# Mineral-Border-Dectetion ( V0.5)

This project aim to help geologists to detect border of minerals on thin sections to then mask them one by one, this with the goal of help in the manual classification and in a future process of automate

# Requirements

- Python 3.6 
- Tensorflow 2.3.1
- opencv 4.5
- keras
- matplotlib

# Instalation and Use 

V1.0 is intended to work on a jupyter notebook: 
 - all the functions are comented
 - Discution cells aim to help future development
 - Any academic intention must be consulted with the authors 
 
# DataSet 
El data set consiste en una conjunto de 1500 imagenes de tamaño 300x250 pixels las cuales estan divididas en los siguientes 6 grupos :
 - Metamorficas PPL (250 imagenes)
 - Igneas PPL (250 imagenes)
 - Sedimentarias PPL (250 imagenes)
 - Metamorficas XPL (250 imagenes)
 - Igneas XPL (250 imagenes)
 - Sedimentarias XPL (250 imagenes)

# methods 
 - Gaussian
 - Bilateral 
 - Meanshift

<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.img-container {
  float: left;
  width: 33.33%;
  padding: 5px;
}

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>Float images side by side:</p>

<div class="clearfix">
  <div class="img-container">
    <img src="https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/main/images/type1/Muestra13.png" width="200">
  </div>
  <div class="img-container">
 <img src="https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/main/images/type2/Muestra13.png" width="200">
  </div>
  <div class="img-container">
 <img src="https://raw.githubusercontent.com/joaramirezra/Mineral-Border-Dectetion/main/images/type3/Muestra13.png" width="200">
  </div>
</div>



</body>
</html>



# Colaborators
 - [Johan Ramírez](https://github.com/joaramirezra)
