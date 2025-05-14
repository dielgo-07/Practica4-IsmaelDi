<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Películas de A24</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .peliculas {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .pelicula {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            width: 300px;
            margin: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .pelicula img {
            width: 100%;
            height: auto;
        }
        .contenido {
            padding: 15px;
        }
        .contenido h2 {
            font-size: 1.2em;
            margin-top: 0;
        }
        .contenido p {
            color: #555;
        }
    </style>
</head>
<body>
    <h1>Películas destacadas de A24</h1>
    <div class="peliculas">
        <div class="pelicula">
            <img src="https://upload.wikimedia.org/wikipedia/en/f/f3/Hereditary.png" alt="Hereditary">
            <div class="contenido">
                <h2>Hereditary</h2>
                <p><strong>Año:</strong> 2018</p>
                <p>Una familia comienza a descubrir oscuros secretos tras la muerte de la abuela, en una historia perturbadora y psicológica.</p>
            </div>
        </div>
        <div class="pelicula">
            <img src="https://upload.wikimedia.org/wikipedia/en/8/8f/Everything_Everywhere_All_at_Once.jpg" alt="Everything Everywhere All at Once">
            <div class="contenido">
                <h2>Everything Everywhere All at Once</h2>
                <p><strong>Año:</strong> 2022</p>
                <p>Una mujer común se ve envuelta en una aventura multiversal donde debe salvar la existencia conectando con otras versiones de sí misma.</p>
            </div>
        </div>
        <div class="pelicula">
            <img src="https://upload.wikimedia.org/wikipedia/en/e/e1/The_Witch_poster.png" alt="The Witch">
            <div class="contenido">
                <h2>The Witch</h2>
                <p><strong>Año:</strong> 2015</p>
                <p>Una familia puritana del siglo XVII enfrenta una presencia siniestra en el bosque en este inquietante cuento de horror folclórico.</p>
            </div>
        </div>
    </div>
</body>
</html>
