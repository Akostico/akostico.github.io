# akostico.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarea</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #181818;
            color: #e5e5e5;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #ff66cc;
            text-align: center;
            padding: 25px 0;
            font-size: 2.5em;
            border-bottom: 3px solid #ff66cc;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
        }
        .blog-posts {
            width: 85%;
            margin: 30px auto;
            padding: 20px;
            background-color: #222;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.6);
        }
        .post {
            background-color: #2a2a2a;
            padding: 25px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
            border-left: 6px solid #ff66cc;
            transition: background-color 0.3s;
        }
        .post:hover {
            background-color: #333;
        }
        .post h2 {
            color: #ff66cc;
            font-family: 'Courier New', Courier, monospace;
            font-size: 1.8em;
            text-decoration: underline;
            margin-bottom: 10px;
        }
        .post p {
            font-size: 1.2em;
            line-height: 1.7em;
            color: #d1d1d1;
        }
        .post a {
            color: #ff66cc;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
            background-color: #444;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .post a:hover {
            background-color: #ff66cc;
            color: #222;
        }
        footer {
            background-color: #333;
            color: #ff66cc;
            text-align: center;
            padding: 15px;
            position: relative;
            width: 100%;
            bottom: 0;
            font-size: 0.9em;
        }
        .stars {
            background: url('https://cdn.pixabay.com/photo/2017/07/04/13/00/blue-2462393_960_720.jpg') repeat;
            padding: 50px 0;
        }
        .button {
            background-color: #ff66cc;
            color: #fff;
            padding: 12px 25px;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #ff3399;
        }
    </style>
</head>
<body>

    <header>
        Tarea
    </header>

    <div class="blog-posts">
        <div class="post">
            <h2>Primer Post: Mis pensamientos</h2>
            <p>Este es mi primer post. Esto fue mas dificil de lo que tenia que ser.</p>
            <a href="#" class="button">Leer más</a>
        </div>

        <div class="post">
            <h2>Segundo Post: pensamientos2</h2>
            <p>Porque esto es tan complicado dios.</p>
            <a href="#" class="button">Leer más</a>
        </div>
    </div>

    <div class="stars">
        <footer>
            <p>Creado para la tarea - &copy; 2025</p>
        </footer>
    </div>

</body>
</html>
