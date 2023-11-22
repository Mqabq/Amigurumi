# Amigurumi
O código HTML define um layout básico de site com uma barra de navegação superior, um carrossel, uma seção de exibição de produtos, uma seção de informações, uma seção de contato e um rodapé. Ele utiliza a estrutura Bootstrap para estilo e capacidade de resposta.

Análise detalhada:

Declaração DOCTYPE: <!doctype html> - Esta linha indica que o documento é um documento HTML5.

Tag HTML: <html lang="pt"> - Esta tag define o elemento raiz do documento HTML e especifica o idioma como Português (pt).

Seção principal:

<head>: esta seção contém meta informações sobre a página HTML.
<meta charset="utf-8">: esta meta tag especifica a codificação de caracteres como UTF-8, garantindo a exibição adequada de conteúdo multilíngue.
<meta name="viewport" content="width=device-width, initial-scale=1">: esta meta tag otimiza o layout do site para vários tamanhos de tela, definindo a largura da janela de visualização como a largura do dispositivo e o nível de zoom inicial como 1.
<title>Home Page Amigurumi</title>: esta tag define o título da página web, que aparece na barra de título do navegador e nos resultados de pesquisa.
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">: esta tag está vinculada ao arquivo Bootstrap CSS, habilitando a estrutura de estilo para o site.
Seção do corpo:

<body>: esta seção contém o conteúdo principal da página da web exibida no navegador.
Barra de navegação:
<nav class="navbar col-12 m-auto position-fixed navbar-expand-lg navbar-dark bg-dark" style="z-index: 999;">: esta seção define a barra de navegação superior usando classes Bootstrap.
<div class="container-fluid col-11 m-auto">: esta div define a largura do contêiner para o conteúdo da barra de navegação.
<a class="navbar-brand" href="#">Amigurumi</a>: Este link define o logotipo do site e links para a página inicial.
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">: Este botão alterna o menu de navegação para dispositivos móveis.
<div class="collapse navbar-collapse" id="navbarSupportedContent">: esta div contém o menu de navegação recolhível.
<ul class="navbar-nav me-auto mb-2 mb-lg-0">: Este elemento ul define os itens do menu de navegação.
<li class="nav-item">: este elemento li define um único item de menu de navegação.
<a class="nav-link active" aria-current="page" href="#">Home</a>: Este link define o item de menu "Home" e o define como ativo para a página inicial.
<li class="nav-item">: Outro elemento li para um item de menu.
<a class="nav-link" href="#Novidades">Novidades</a>: Este link define o item de menu "Novidades".
<li class="nav-item">: Outro elemento li para um item de menu.
<a class="nav-link" href="#Contato">Contato</a>: Este link define o item de menu "Contato".
Carrossel:
<div id="carouselExampleIndicators" class="carousel slide">: esta seção define o carrossel usando classes Bootstrap.
<h2 class="text-center">Novidades</h2>: Esta rubrica apresenta o título "Novidades".
<div class="carousel-indicators">: Esta div contém os indicadores do carrossel para seleção de slides.
<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>: Este botão define o indicador do primeiro slide.
<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>: Indicador para o segundo slide.
`<button type="button" data-bs-target="#carouselExample
Fontes
