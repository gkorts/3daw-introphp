<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de 1 a 100</title>
</head>
<body>

    <h1>Lista de números</h1>

    <ol>
        <?php
        for ($i = 1; $i <= 100; $i++) {
            echo "<li>$i</li>";
        }
        ?>
    </ol>

</body>
</html>