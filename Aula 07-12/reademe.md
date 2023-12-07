Iniciando o conteudo CSS
existe tres modos de incluir css
 CSS Inline
 quando da estilo na mesma linha do arquivo.
 EX:
 </head>
<body>
    <div style="background-color: aqua;">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nemo, eum.</p>
    </div> 
</body>
</html>

Segue abaixo outro exemplo de como usar o CSS.

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Start CSS</title>

    <style>
        .container{background-color: brown;}
    </style>
</head>

<body>
<Div class="container">
<p> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus, placeat!</p>
</Div>

</body>
</html>



Seletor de clesse/id


#. para id
. para classe

EX:
container{
    background-color: yellowgreen;

}
#container {
    background-color: blueviolet;

}

Seletor de tag
atraves da Div no CSS

div{
background-color: blue;

}


PROPRIEDADES E VALORES
propriedades e valores

Reset de Css

limpa as margens.
EX:

body{
    margin: 0;
    padding: 0;
}
unidade de medida
Pixel
Em
rem
%
vl
vw
EX:
.container {
    background-color: rgb(157, 157, 184);
    height: 500px;
    width: 500px;
}unidade de medida EM 
1 EM equivale a 16px
1 REM equivale a 18px
Vw unidade de medida relativa