Estrutura Básica:
Uma página HTML é composta por uma estrutura básica que inclui as seguintes partes:

html

<!DOCTYPE html>
<html>
<head>
    <title>Título da Página</title>
</head>
<body>
    <!-- O conteúdo da sua página vai aqui -->
</body>
</html>

    <!DOCTYPE html> define o tipo de documento como HTML5.
    <html> é o elemento raiz que envolve todo o conteúdo da página.
    <head> contém informações sobre a página, como o título.
    <title> define o título da página que é exibido na aba do navegador.
    <body> contém o conteúdo visível da página.

Cabeçalho (Head):
A seção <head> contém metadados e informações sobre a página, como links para folhas de estilo (CSS), meta tags e o título da página. Aqui está um exemplo simples de como adicionar um link para um arquivo CSS externo:

html

<head>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>

Corpo (Body):
A seção <body> é onde você coloca o conteúdo visível da página. Aqui você pode adicionar texto, imagens, links e outros elementos HTML. Por exemplo:

html

<body>
    <h1>Meu Primeiro Título</h1>
    <p>Este é um parágrafo de texto.</p>
    <img src="imagem.jpg" alt="Minha Imagem">
    <a href="https://www.unescnet.br/">Link para o Exemplo</a>
</body>

    <h1> é um cabeçalho de nível 1 (o maior) usado para títulos principais.
    <p> é um elemento de parágrafo para texto.
    <img> é usado para exibir imagens.
    <a> é usado para criar links para outras páginas.

Comentários:
Você pode adicionar comentários em seu código HTML para fazer anotações. Eles não são visíveis para os usuários, mas podem ajudá-lo a entender seu próprio código.

html

<!-- Este é um comentário em HTML -->
