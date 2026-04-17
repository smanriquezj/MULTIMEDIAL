# MULTIMEDIAL

#### Exploración creativa de arte, tecnología y medios digitales interactivos

13/03
Ejercicio 1

https://smanriquezj.github.io/MULTIMEDIAL/w/index.html

https://mauricixx.github.io/multimedial/


```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

17/04

Index

```
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Mi pagina</title>

<style>
body{
  background-color: white;
  color: blanck;
  margin: 0;
  font-family: Arial, sans-serif;
  font-size: 60px;
  text-align: center;
  padding-top: 50px;
}

h1{
  font-size: 90px;
  text-align: center;
  margin-top: 10px;
}

img{
  width: 30%;
  height: auto;
  display: block;
  text-align: center;
  margin: 10px auto 30px auto;
}

a{
  color: black;
  font-size: 24px;
  text-align: center;
  margin: 0 40px;
}


</style>

</head>
<body>

<h1>This is My sitio</h1>

<!-- <a href="pagina2.html">Ir a la segunda página</a>-->

<a href="obra.html">Obra</a><br>

<a href="contacto.html">Contacto</a>
</body>

</html>
```

Obra

```
<!DOCTYPE html>
<html>
<head>
<title>MIs obras</title>
</head>

</head>

<body>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>


    <!-- Contenedor principal -->
    <div class="contenedor">
            <div class="Titulo">
                <h1>Mis obras</h1>
                <a href="index.html">Inicio</a><br>
                <a href="contacto.html">Contacto</a>
        </div>

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <h2>    Sin Titulo 1</h2>
            <img src="img/sintitulo1.jpg">
            <p>
                Este es un texto de ejemplo. Aquí puedes escribir contenido descriptivo,
                reflexivo o informativo sobre la imagen.
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="imagen2.jpg" alt="Descripción de la imagen">
            <h2>Título 2</h2>
            <p>
                Otro texto que acompaña la imagen. Puedes trabajar narrativa,
                análisis visual o cualquier tipo de contenido.
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="imagen3.jpg" alt="Descripción de la imagen">
            <h2>Título 3</h2>
            <p>
                Este es un tercer bloque. Puedes repetir esta estructura
                tantas veces como quieras.
            </p>
        </div>

    </div>


    

    <div class="Contenedor">

    </div>


</body>
</html>
```
