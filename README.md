# Guia de estilos | Style guide

Toda a estilização do projeto encontra-se no projeto do figma.

Check the figma design for the style guide.

## Componentes | Components

### Cabeçalho | Header

<header class="container cabecalho">
    <img src="assets/img/logo.svg" alt="Logo da casa verde" class="cabecalho__logo">
    <a href="#" aria-label="Meu carrinho">
        <img src="assets/img/icones/carrinho.svg" alt="Ícone do carrinho de compras" class="cabecalho__carrinho">
    </a>
</header>

### Cartão generico | Generic card

<article class="cartao">
    <h2 class="titulo alinhamento--meio">Como conseguir
        <span class="titulo--destaque">minha planta</span>
    </h2>
    <ul class="lista-item">
        <li class="item">
            <span class="item__icone item__icone--cursor"></span>
            <p>Escolha suas plantas</p>
        </li>
        <li class="item">
            <span class="item__icone item__icone--carrinho"></span>
            <p>Faça seu pedido</p>
        </li>
        <li class="item">
            <span class="item__icone item__icone--caminhao"></span>
            <p>Aguarde na sua casa</p>
        </li>
    </ul>
</article>

### Cartão de produto | Product card

<article class="produto">
    <img src="assets/img/produto-01.png" alt="Foto do produto" class="produto__imagem">
    <div class="produto__conteudo">
        <h3 class="produto__titulo titulo--destaque">Ajuga reptans</h3>
        <p class="produto__preco">R$ 20,00</p>
        <a href="#" class="produto__comprar">Comprar<span class="produto__comprar--icone"></span></a>
    </div>
</article>

### Cartão de vídeo | Video card

<article class="cartao-de-video">
    <div class="cartao-de-video__video">
        <img src="https://picsum.photos/278/252" alt="Banner do vídeo">
    </div>
    <h3 class="cartao-de-video__titulo">Vídeo XYZ</h3>
    <p>Publicado em março de 2019</p>
</article>

### Rodapé | Footer

<footer class="container rodape">
    <img src="assets/img/logo.svg" alt="Logo da casa verde" class="rodape__logo">
    <ul class="rodape__social">
        <li><a href="#" class="rodape__social--midia"><img src="assets/img/icones/facebook.svg" alt="Ícone do facebook" title="Facebook"></a></li>
        <li><a href="#" class="rodape__social--midia"><img src="assets/img/icones/twitter.svg" alt="Ícone do twitter" title="Twitter"></a></li>
        <li><a href="#" class="rodape__social--midia"><img src="assets/img/icones/instagram.svg" alt="Ícone do instagram" title="Instagram"></a></li>
    </ul>
    <address class="rodape__unidade texto">
        <span class="rodape__unidade-titulo">Rio de Janeiro</span>
        Rua Siqueira Campos, 171, 303<br>
        Copacabana<br>
        Telefone: (21) 99876-0099
    </address>
    <address class="rodape__unidade texto">
        <span class="rodape__unidade-titulo">São Paulo</span>
        Rua Anita Garibaldi, 33, 13<br>
        Sé<br>
        Telefone: (11) 99875-2201
    </address>
</footer>