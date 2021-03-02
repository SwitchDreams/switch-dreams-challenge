# Switch Dreams Challenge

Iremos propor um desafio para avaliar suas habilidades com o framework Ruby on Rails, sendo isso parte do processo seletivo para vaga de desenvolvedor backend e frontend aqui na Switch Dreams.

Esperamos que você tenha uma boa noção nos seguintes tópicos:

- HTTP e estrutura básica da web
- Linguagem de programação Ruby
- Framework Ruby on Rails
- HTML/CSS e Javascript
- Banco de Dados relacional
- Modelo MVC

Além disso é sempre interessante estar atento aos padrões usuais de qualidade de código.

## Problema

A biblioteca da Universidade BnU está digitalizando seus livros e te contratou para desenvolver o sistema que organizará o acervo. Cada livro terá título, autor, ano de publicação, foto de capa, etc. Seu conteúdo será um pdf, que deverá ser aberto no browser do cliente, para que o aluno possa desfrutar do material sem realizar downloads.

Como a biblioteca possui muitos livros, foi proposto o sistema de **tags** para organizar o material. Cada tag terá um nome e pertencerá a uma das seguintes categorias:

- Semestre
- Disciplina
- Outros
- Licenciatura
- Bacharelado

Dessa forma, cada tag poderá estar em diversos livros e cada livro poderá ter diversas tags. A título de exemplo, o livro de Cálculo 1 poderá ter as seguintes tags:

- "1 semestre" e "2 semestre", para a categoria **semestre**
- "Cálculo", para a categoria **disciplina**
  
Essas tags serão utilizadas em um filtro na página de listagem dos livros. Para o exemplo acima, o livro de Cálculo 1 deve ser retornado caso qualquer uma das tags esteja presente na seleção, ou seja, se ao menos uma tag do livro estiver presente na seleção, este deverá ser retornado.

A página principal deve conter a listagem dos livros com os filtros em cima, tendo possibilidade de filtrar pelas tags ou pelo nome.

## Requisitos

Para iniciar o desafio, crie um repositório e inicie seu projeto rails nele. Coloque um readme com todas as informações que você julgar pertinente para o desafio. Para entregar a sua implementação, você deve nos enviar o link do repositório e fazer um deploy no [heroku](https://www.heroku.com/) (explicite no readme a url do deploy)

Para padronizar o desafio você deve usar o Postgres como banco de dados (exigido pelo heroku) e a versão do Rails pode ser a 5.x ou 6.x com preferência para a 6. Sugerimos também que utilize a versão 2.7.x do ruby, para que você possa usar as features mais novas da linguagem.

A aplicação deve ser em Rails fullstack, ou seja, tanto o backend quanto o frontend devem utilizar o pipeline do Rails para servir páginas html para o cliente. Isso basicamente quer dizer que o seu frontend deverá estar contido nos arquivos `.html.erb`.

## Avaliação

Avaliaremos as seguintes habilidades

- Nível de conhecimento em Rails
- Nível de conhecimento em Ruby
- Nível de conhecimento em front-end
- Testes no código
- Utilização do github

## Observações
Ao enviar o desafio você declara que a solução implementada foi 100% feita por você, sem violar nenhuma licença de software de terceiros.

