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
 - 6 types each type of rock has 250 images each one with a 300x250 pixels
 

 

 - looking for one 

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
