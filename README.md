# Page
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #f4f4f4;
        }

        .container {
            text-align: center;
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,.15);
        }

        h1 {
            color: #2c3e50;
        }

        button {
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            background: #007BFF;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>¡Hola, mundo!</h1>
    <p>Esta es mi primera página web.</p>

    <button onclick="saludar()">
        Haz clic aquí
    </button>
</div>

<script>
function saludar() {
    alert("¡Bienvenido!");
}
</script>

</body>
</html>
