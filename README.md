<hi>Configurar un repositorio nuevo desde terminal</hi>
<ol>
    <li> git init </li> <!-- Inicializa un repositorio vacio en nuestra carpeta -->
    <li> git add </li> <!-- Agrega archivos nuevos y con cambios a la version actual -->
    <li> git commit -m "Deja un mensaje" </li> <!-- Crea una version nuev con los cambios actuales -->
    <li> Ir a Github y crea un repositorio vacio </li> <!-- Inicializa el repositorio de nuestra cuenta actual -->
    <li> git add remote origin url-del-github-vacio </li> <!-- Enlaza el repositorio de nuestra cuenta con el repositorio de nuestra carpeta -->
    <li> git push -u origin master </li> <!-- Actualiza la version actual de nuestra carpeta en el repositorio de nuestra cuenta -->
</ol>

<h1> Generar una nueva version y actualizar el repositorio </h1>
<ol>
    <li> git add </li> <!-- Inicializa un repositorio vacio en nuestra carpeta -->
    <li> git commit -m "Un nuevo mensaje" </li> <!-- Crea una version nuev con los cambios actuales -->
    <li> git push -u origin main </li> <!-- Actualiza la version actual de nuestra carpeta en el repositorio de nuestra cuenta -->
</ol>

<h1> Verificar el estatus del repositorio </hi>
<ol>
    <li> git status </li> <!-- Muestra el estado -->
</ol>