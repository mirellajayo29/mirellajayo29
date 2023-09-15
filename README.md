<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campus Virtual - Colegio Raul Porras Barrenechea</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFFFF0; /* Amarillo claro */
        }
        header {
            background-color: #FFD700; /* Amarillo */
            color: white;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        h1 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #000; /* Negro */
        }
        .course {
            background-color: #FFF;
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .course h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #000; /* Negro */
        }
        .course p {
            color: #666;
        }
        .options {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }
        .options a {
            text-decoration: none;
            color: #333;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: background-color 0.2s;
        }
        .options a:hover {
            background-color: #FFD700; /* Amarillo */
        }
        .task {
            background-color: #FFF;
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .task h3 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #000; /* Negro */
        }
        .task p {
            color: #666;
        }
        .task-details {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .task-date {
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Campus Virtual - Colegio Raul Porras Barrenechea</h1>
    </header>
    <div class="container">
        <div class="course">
            <h2>Computación</h2>
            <p>Profesor: Juan Pérez</p>
        </div>
        <div class="options">
            <a href="#">Tareas</a>
            <a href="#">Mensajería</a>
            <a href="#">Calificaciones</a>
        </div>
        <div class="task">
            <h3>Tarea 1</h3>
            <p>Realizar una presentación sobre programación web.</p>
            <div class="task-details">
                <p class="task-date">Fecha límite: 20 de septiembre, 10:00 AM</p>
                <a href="#">Subir Tarea</a>
            </div>
        </div>
        <div class="task">
            <h3>Tarea 2</h3>
            <p>Resolución de problemas de algoritmos.</p>
            <div class="task-details">
                <p class="task-date">Fecha límite: 25 de septiembre, 11:30 AM</p>
                <a href="#">Subir Tarea</a>
            </div>
        </div>
    </div>
</body>
</html>
