

## 5. Adaptação para Table-Based Layout

### O que é Table-Based Layout?

Table-based layout é uma técnica de construção de páginas web que utiliza tabelas HTML (`table`, `tr` e `td`) para organizar visualmente os elementos, como cabeçalho, menu, conteúdo e rodapé.

### Por que é considerada uma técnica antiga?

Essa abordagem foi bastante utilizada nos primeiros anos da web, quando as ferramentas modernas de layout ainda não existiam ou não eram amplamente suportadas.

Atualmente, CSS Flexbox e CSS Grid permitem criar layouts mais flexíveis e responsivos, sem utilizar tabelas para organizar visualmente toda a página.

As tabelas continuam sendo apropriadas para apresentar dados tabulares, como planilhas e comparações. O problema não é usar tabelas, mas utilizá-las como estrutura geral do layout.

### Dificuldades encontradas na adaptação

Durante a adaptação do projeto, algumas dificuldades foram:

- Organizar o menu e o conteúdo em colunas usando linhas e células.
- Utilizar `colspan` para fazer o cabeçalho e o rodapé ocuparem toda a largura.
- Manter o código organizado mesmo com a estrutura baseada em tabelas.
- Adaptar a apresentação para telas pequenas.
- Perceber que a tabela organiza a aparência, mas não comunica claramente o significado de cada área da página.

### Comparação com a estrutura semântica moderna

No modelo baseado em tabelas, utilizamos elementos como `table`, `tr` e `td` para organizar as áreas visualmente.

Na estrutura semântica moderna, utilizamos elementos de acordo com sua finalidade, como `header`, `nav`, `main`, `section` e `footer`, combinados com CSS para controlar o layout.

Exemplo moderno:

```html
<header>
  <h1>Desenvolvimento Web</h1>
</header>

<nav aria-label="Navegação principal">
  <a href="#inicio">Início</a>
  <a href="#html">HTML</a>
  <a href="contato.html">Contato</a>
</nav>

<main>
  <section id="inicio">
    <h2>Bem-vindo</h2>
    <p>Aprenda os fundamentos do desenvolvimento web.</p>
  </section>

  <section id="html">
    <h2>HTML</h2>
    <p>O HTML organiza o conteúdo das páginas.</p>
  </section>
</main>

<footer>
  <p>Projeto de Desenvolvimento Web — 2026</p>
</footer>
```

### Conclusão

O table-based layout permite compreender como páginas antigas eram organizadas, mas apresenta limitações de manutenção, responsividade e significado semântico.

Para projetos atuais, a recomendação é utilizar HTML semântico combinado com CSS Grid ou Flexbox. As tabelas devem ser reservadas principalmente para dados que realmente precisam ser apresentados em formato tabular.
