Estilos Inline:
Você pode adicionar estilos diretamente a elementos HTML usando o atributo style. Isso é útil para estilos específicos em elementos individuais.

html

<h1 style="color: blue; font-size: 24px;">Título Estilizado</h1>
<p style="font-family: Arial, sans-serif;">Este é um parágrafo estilizado.</p>

Estilos Internos:
Você pode incluir estilos internamente na seção <head> do documento HTML usando a tag <style>. Isso permite que você defina estilos para várias partes da página.

html

<head>
    <style>
        h1 {
            color: blue;
            font-size: 24px;
        }

        p {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Título Estilizado</h1>
    <p>Este é um parágrafo estilizado.</p>
</body>

Estilos Externos:
A abordagem recomendada é criar um arquivo CSS externo e vinculá-lo à sua página HTML usando a tag <link>. Isso mantém o código mais organizado e permite que você reutilize estilos em várias páginas.

Crie um arquivo CSS separado (por exemplo, estilo.css):

css

/* estilo.css */
h1 {
    color: blue;
    font-size: 24px;
}

p {
    font-family: Arial, sans-serif;
}

Em seu arquivo HTML, vincule o CSS externo:

html

<head>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
    <h1>Título Estilizado</h1>
    <p>Este é um parágrafo estilizado.</p>
</body>

Classes e IDs:
Você pode aplicar estilos a elementos específicos usando classes e IDs. Isso permite maior controle e reutilização de estilos.

html

<head>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
    <h1 class="destaque">Título Estilizado</h1>
    <p id="paragrafo">Este é um parágrafo estilizado.</p>
</body>

No arquivo CSS:

css

/* estilo.css */
.destaque {
    color: blue;
    font-size: 24px;
}

#paragrafo {
    font-family: Arial, sans-serif;
}
