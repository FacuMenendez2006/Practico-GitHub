# Práctico GitHub

Este es un ejemplo de cómo tener un archivo HTML y uno CSS separados

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Bienvenido al Práctico GitHub</h1>
    <div class="container">
        <p>Este es un ejemplo de HTML y CSS separados.</p>
    </div>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  margin: 0;
  padding: 0;
}

h1 {
  color: #333;
  text-align: center;
  margin-top: 40px;
}

.container {
  max-width: 800px;
  margin: 40px auto;
  background: #fff;
  padding: 24px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
