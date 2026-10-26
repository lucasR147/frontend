Diferença entre div e HTML semântico
A tag <div> é um elemento genérico do HTML utilizado para agrupar outros elementos e organizar o conteúdo de uma página. Ela não possui um significado semântico próprio.

Já o HTML semântico utiliza tags que descrevem o propósito do conteúdo, como <header>, <nav>, <main>, <section>, <article> e <footer>.

O uso de elementos semânticos facilita a leitura do código, melhora a acessibilidade e ajuda os mecanismos de busca a compreender a estrutura da página.

  BLOCOS GENÉRICOS

<div class="cabecalho">
  <h1>Meu site</h1>
</div>

<div class="navegacao">
  <a href="#inicio">Início</a>
  <a href="#sobre">Sobre</a>
</div>

<div class="conteudo">
  <h2>Bem-vindo!</h2>
  <p>Este é o conteúdo principal da página.</p>
</div>

<div class="rodape">
  <p>Todos os direitos reservados.</p>
</div>

BLOCOS SEMÂNTICOS
<header>
  <h1>Meu site</h1>
</header>

<nav aria-label="Navegação principal">
  <a href="#inicio">Início</a>
  <a href="#sobre">Sobre</a>
</nav>

<main>
  <section id="inicio">
    <h2>Bem-vindo!</h2>
    <p>Este é o conteúdo principal da página.</p>
  </section>
</main>

<footer>
  <p>Todos os direitos reservados.</p>
</footer>

Conclusão
A tag <div> continua sendo útil para agrupar elementos quando não existe uma tag semântica mais apropriada. Entretanto, sempre que possível, devemos utilizar elementos semânticos para tornar o código mais organizado, acessível e fácil de compreender.

Mensagem de commit sugerida:

docs: adiciona README sobre HTML semântico e div.

