# Iniciais
<!DOCTYPE html>
<html lang="pt-BR" >
    <head>
        <title>Primeiro Projeto</title>
        <meta charset="utf-8">
        <meta name="author"  content="Lucas Rover">
        <meta http-equiv="refresh"  content="5">
        <script>
        function sorteioNumero () {
            resultado.innerHTML = Math.random ( ) * 10
        }
        window.onload = sorteioNumero;
    </script>
    </head>    
    <body>
     <style> 
        body{ 
            background: #F00; 
        }
      </style>
      <p id="resultado"> </p>
    </body>
</html>
