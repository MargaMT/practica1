
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gestor de Tareas</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="shortcut icon" href="//virtual.uno.edu.mx/pluginfile.php/1/theme_academi/favicon/1742059256/apple-touch-icon-32-precomposed.ico" />
</head>
<body>   
      <img src="logouno.png" alt="UNOVIRTUAL">
                       
  <h1>Gestor de Tareas</h1>

  <input type="text" id="entradaTarea" placeholder="Escribe una tarea" />
  <button id="botonAgregar">Agregar</button>

  <div class="controles">
    <button onclick="filtrarTareas('todas')">Todas</button>
    <button onclick="filtrarTareas('completadas')">Completadas</button>
    <button onclick="filtrarTareas('pendientes')">Pendientes</button>
    <button onclick="ordenarTareas()">Ordenar A-Z</button>
  </div>

  <ul id="listaTareas"></ul>
<hr>
  <script src="index.js"></script>
 
  <footer>
  &copy; 2025 Graciela Mis y Roberto Gutierrez. Todos los derechos reservados.
</footer>

</body>
</html>
