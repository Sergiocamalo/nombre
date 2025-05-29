# nombre
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Juego de Adivinar Número</title>
</head>
<body>
  <p>Ingrese un número entre 1 y 10:</p>
  <input type="number" id="numeroUsuario" min="1" max="10">
  <button onclick="jugar()">Jugar</button>

  <p id="resultado"></p>

 <script>
    let selec = parseInt(prompt('Ingrese un valor entre 1 y 10'));
    let num = parseInt(Math.random() * 10) + 1;
    if (num == selec)
        document.write('Ganó el número que se sorteó es el ' + num);
    else
        document.write('Lo siento se sorteó el valor ' + num + ' y usted eligió ' + selec);

   document.write('Hola soy Raúl');
</script>

</body>
</html>
