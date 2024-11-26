<div class="container">
  <input type="checkbox" id="menu" class="container__botao" />

  <span class="cabeçalho__menu-hamburguer container__imagem"></span>
  <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem" />
</div>
<label for="menu">
  <span class="cabeçalho__menu-hamburguer container__imagem"></span>
</label>
<div class="container">
  <input type="checkbox" id="menu" class="container__botao" />
  <label for="menu">
    <span class="cabeçalho__menu-hamburguer container__imagem"></span>
  </label>
  <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem" />
</div>
<label for="menu">
  <span class="cabeçalho__menu-hamburguer container__imagem"></span>
</label>

<ul class="lista-menu">
</ul>
<ul class="lista-menu">
  <li class="lista-menu__titulo">Categorias</li>
  <li class="lista-menu__item"></li>
  <li class="lista-menu__item"></li>
  <li class="lista-menu__item"></li>
  <li class="lista-menu__item"></li>
  <li class="lista-menu__item"></li>
</ul>
<ul class="lista-menu">
  <li class="lista-menu__titulo">Categorias</li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Programação</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Front-end</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Infraestrutura</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Business</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Design & UX</a>
  </li>
</ul>
.lista-menu {
  display: none;
}
.container__botao:checked ~ .lista-menu {
  display: block;
}
.cabecalho {
  background-color: var(--branco);
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
}
.lista-menu {
  display: none;
  position: absolute;
  top: 100%;
}
<section class="contato"></section>
<section class="contato">
  <h2>Fique por dentro das novidades!</h2>
  <p>Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" />
</section>
<section class="contato">
  <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
  <p class="contato__texto"> Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" class="contato__email"/>
</section>
@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");
