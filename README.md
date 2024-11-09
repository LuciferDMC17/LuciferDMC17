<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumpleaños</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f3f3f3;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
        }
        .tulips {
            display: flex;
            justify-content: center;
        }
        .tulip {
            background-color: #ff9999;
            width: 30px;
            height: 60px;
            border-radius: 15px 15px 0 0;
            position: relative;
            margin: 5px;
        }
        .tulip::before {
            content: '';
            position: absolute;
            width: 0;
            height: 0;
            border-left: 15px solid transparent;
            border-right: 15px solid transparent;
            border-bottom: 20px solid #ff9999;
            top: -20px;
            left: 0;
        }
        .tulip::after {
            content: '';
            position: absolute;
            width: 2px;
            height: 100px;
            background-color: #339966;
            top: 60px;
            left: 14px;
        }
        .message {
            margin-top: 20px;
            font-size: 24px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="tulips">
            <div class="tulip"></div>
            <div class="tulip"></div>
            <div class="tulip"></div>
            <div class="tulip"></div>
            <div class="tulip"></div>
        </div>
        <div class="message">Feliz cumpleaños</div>
    </div>
</body>
</html>


<!---
LuciferDMC17/LuciferDMC17 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
