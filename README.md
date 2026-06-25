<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practice W3school part 14</title>
</head>
<body>

<!--Attribut picture digunakan ketika jaringan dalam kondisi tidak stabil-->
<picture>
  <source media="(min-width: 650px)" srcset="image.png">
  <source media="(min-width: 465px)" srcset="sample.jpeg">
  <img src="tab.jpeg">
</picture>

 <br>
<!--Format Support-->

<picture>
  <source srcset="Image.png">
  <source srcset="sample.png">
  <img src="Earth.png" alt="Earth" style="width:auto;">
</picture>

<!--Favicon-->

<link rel="icon" type="image/x-icon" href="Image.png">
    
</body>
