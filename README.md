<html>
    <header>
        <title>practica 1 </title>
    </header>
    <body>
         <p id="resultado"></p>
        <script>
const numero = -3; // Cambia este valor para probar
const resultado = document.getElementById("resultado");

if (numero > 0) {
resultado.textContent = `${numero} es positivo`;
} else if (numero < 0) {
resultado.textContent = `${numero} es negativo`;
} else {
resultado.textContent = `El número es cero`;
}
</script>
    </body>
</html>
