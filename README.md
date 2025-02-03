<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <title>DevSorteio</title>
</head>

<body>

<img src="./img/Sorteionoinstagram.jpg" alt="img sorteio">

    <h2> Sortear um Número</h2>
    <div>
        <input placeholder="entre" class="input-min" type="number">
        <input placeholder="e" class="input-max" type="number">
    </div>

    <button onclick="generateNumber()">Sortear</button>
</body>

<script src="./scripts.js"></script>


</html>
