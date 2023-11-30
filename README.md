# Seed & Coortex - Full Stack Developer Challenge
Desafio para você que quer trabalhar conosco!

## Instruções

<ol>
  <li>Clone este repositório</li>
  <li>Seu objetivo principal é transformar o desafio em um protótipo funcional.</li>
  <li>Crie um diretório chamado src no projeto e coloque todos os arquivos que você criar dentro dessa pasta.</li>
  <li>Após concluir o desafio, envie o código por e-mail para a pessoa do time que lhe forneceu as instruções.</li>
</ol>

## Desafio

<p>
  O desafio consiste em criar uma ferramenta de busca chamada MultiSearch. O usuário deverá digitar um texto e, como resultado, serão listados todos os objetos do sistema que correspondam à busca.

  O sistema em questão é um ERP que armazena informações como Pedidos de Venda, Pedidos de Compra, Dados de Produtos, Dados de Equipamentos e Dados de Mão de Obra.

  O MultiSearch irá pesquisar em todas essas tabelas e mostrar os dados agrupados.

  O desafio foi dividido em duas partes principais para avaliar suas habilidades de Full Stack.
</p>

## Frontend

No lado do Frontend, o desafio será criar uma tela que simule o resultado da nossa busca.
Para isso:

- HTML5/CSS3/JS e  noções básicas de design
- Faça bom uso das tags HTML5 e CSS3
- Utilizar [AngularJS](https://angularjs.org) ou ([React](https://github.com/facebook/react), [Angular2+](https://github.com/angular/angular), [Vue.js](https://github.com/vuejs/vue))
- A pasta "layout" possui uma imagem de referência para o resultado e a logomarca já exportada para caso precise
- Inicialmente, crie um arquivo JSON chamado "data.json" com os dados de exemplo que serão utilizados para renderizar sua aplicação
- Sua aplicação deverá consultar seu arquivo JSON e responder com os objetos encontrados, simulando a consulta a uma API
- Tornar o projeto responsivo
- Fique a vontade para usar [Bootstrap](https://getbootstrap.com), pode ser uma boa ideia para acelerar o processo de design

## Backend

No lado do Backend, o desafio será criar uma API REST para o nosso buscador.
Siga as seguintes instruções:

- Crie um projeto de API REST preferencialmente com [ASP.NET](https://www.asp.net) (ou [Node.js](https://nodejs.org) com Typescript).
- Na pasta "data", há um arquivo JSON para cada tabela do sistema, representando o banco de dados. Sua aplicação deverá ler esses arquivos durante a busca.
- Exponha um serviço de consulta que receba uma string com o texto buscado e retorne com os objetos encontrados em todas as tabelas do sistema
- Normalize os dados antes de enviar para o cliente.
- Criar uma documentação da API utilizando swagger ou outra ferramenta similar.

### Recursos Bônus (opcional)

- Implementar testes e2e

## Integração Frontend e Backend

Agora, junte tudo que foi feito anteriormente:

Assim:
- O arquivo JSON criado no Frontend para simular os dados não será mais necessário, pois o backend já retornará os dados necessários. Portanto, substitua a função de leitura desse arquivo pela função de envio de requisição para o backend.
- Quando o usuário digitar um texto na tela, ele será enviado para o backend.
- O backend lerá os arquivos de dados e buscará quais objetos correspondem ao texto buscado.
- O backend retornará uma lista dos resultados encontrados.
- O frontend exibirá os resultados agrupados por tipo de objeto.


##  Dicas?

Foque nas funcionalidades principais do desafio.

Keep it Simple!  :)

## O que será avaliado
Em ordem, os principais pontos que serão avaliados ao submeter o desafio:
1. **Código limpo e organizado:** Avaliaremos a estrutura do código, a legibilidade e a clareza das nomenclaturas, a consistência na utilização de boas práticas de programação e a organização dos arquivos e pastas.
2. **Funcionalidade:** Verificaremos se a aplicação atende aos requisitos solicitados no desafio, como a busca correta dos objetos no backend, a exibição adequada dos resultados no frontend e a correta agrupação dos objetos.
3. **Qualidade do código:** Analisaremos a qualidade do código em relação à eficiência, escalabilidade, segurança e manutenibilidade. Também observaremos o tratamento de erros e exceções de forma adequada.
4. **Boas práticas de desenvolvimento:** Serão avaliadas as boas práticas de desenvolvimento, como a modularização do código, a utilização adequada de bibliotecas e frameworks, e a implementação de um design responsivo e amigável.
5. **Conhecimento das tecnologias utilizadas:** Observaremos o conhecimento e a utilização adequada das tecnologias solicitadas, como AngularJS (ou outra opção), ASP.NET (ou Node.js) e outras bibliotecas/frameworks relacionadas.
6. **Documentação e comentários:** Será avaliada a clareza da documentação e dos comentários presentes no código, que devem auxiliar na compreensão e manutenção do sistema.
7. **Bônus:** Os recursos bônus implementados serão avaliados de acordo com a qualidade, a eficiência e a funcionalidade adicionada à aplicação.

<br/>

#### Em caso de dúvidas, abra uma [issue](https://github.com/Admin-Seed/dev-challenge/issues). ;)

<br/>

#### Até logo e bom trabalho!
Seed & Coortex team
