<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>FORMULÁRIO: CAMPO TIPO SELECT</h1>
    <form method="post">
        <label for="fruta">Fruta</label>
        <select name=" Fruta">
            <option value="abacaxi">Abacaxi</option>
            <option value="laranja">Laranja</option>
            <option value="uva">Uva</option>
            <option value="morango">Morango</option>
        </select>
        <BR>
        <BR>
        <label for="verdura">Verdura</label>
        <select name="Verdura" multiple size="3">
            <option value="acelga">Acelga</option>
            <option value="alface">Alface</option>
            <option value="brocolis" selected>Brócolis</option>
            <option value="couve">Couve</option>
            <option value="espinafre">Espinafre</option>
    </form>
</body>
</html>
