<!DOCTYPE html>
<html>
<head>
  <title>Selección de productos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .producto {
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 10px;
    }
    .producto img {
      width: 100px;
      height: 100px;
      margin-right: 10px;
    }
    .producto h2 {
      font-size: 18px;
      margin-top: 0;
    }
    .boton {
      background-color: #4CAF50;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .boton:hover {
      background-color: #3e8e41;
    }
  </style>
</head>
<body>
  <h1>Selección de productos</h1>
  <div class="producto">
    <img src="producto1.jpg" alt="Producto 1">
    <h2>Producto 1</h2>
    <p>Descripción del producto 1</p>
    <button class="boton" onclick="redirigirWhatsApp()">Seleccionar</button>
  </div>
  <div class="producto">
    <img src="producto2.jpg" alt="Producto 2">
    <h2>Producto 2</h2>
    <p>Descripción del producto 2</p>
    <button class="boton" onclick="redirigirWhatsApp()">Seleccionar</button>
  </div>
  <div class="producto">
    <img src="producto3.jpg" alt="Producto 3">
    <h2>Producto 3</h2>
    <p>Descripción del producto 3</p>
    <button class="boton" onclick="redirigirWhatsApp()">Seleccionar</button>
  </div>
  <script>
    function redirigirWhatsApp() {
      window.location.href = "(link unavailable).";
    }
  </script>
</body>
</html>
