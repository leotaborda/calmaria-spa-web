# Calmaria SPA

## Descrição

O "Calmaria SPA" é um site desenvolvido para apresentar os serviços de um spa que oferece tratamentos de relaxamento e bem-estar. O objetivo principal do site é fornecer informações sobre os serviços oferecidos, permitir o agendamento de horários e fornecer informações de contato para os clientes.

## Funcionalidades

As principais funcionalidades do site incluem:

*   **Página inicial:** Apresenta os serviços do spa, depoimentos de clientes e informações de contato.
*   **Página de serviços:** Detalha os tratamentos oferecidos, seus benefícios e preços.
*   **Página de agendamento:** Permite que os clientes agendem horários para os tratamentos online.
*   **Página de contato:** Fornece informações de contato do spa, como endereço, telefone e e-mail.

## Tecnologias utilizadas

O site foi desenvolvido utilizando as seguintes tecnologias:

*   HTML
*   CSS
*   SASS
*   [Outras tecnologias que você utilizou]

## Estrutura do projeto

A estrutura do projeto é organizada da seguinte forma:

*   `index.html`: Arquivo HTML principal do site.
*   `css/`: Pasta que contém os arquivos CSS compilados.
*   `sass/`: Pasta que contém os arquivos SASS.
    *   `_base.scss`: Arquivo que contém estilos básicos para o site.
    *   `_variables.scss`: Arquivo que define as variáveis utilizadas no projeto (cores, fontes, etc.).
    *   `_mixins.scss`: Arquivo que define os *mixins* utilizados no projeto.
    *   `_header.scss`: Arquivo que contém os estilos do cabeçalho do site.
    *   `_footer.scss`: Arquivo que contém os estilos do rodapé do site.
    *   [Outros arquivos SASS que você criou]
*   `js/`: Pasta que contém os arquivos JavaScript.
*   `img/`: Pasta que contém as imagens utilizadas no site.

## SASS

O SASS foi utilizado para organizar e modularizar o código CSS do site. As principais funcionalidades do SASS utilizadas no projeto incluem:

*   **Variáveis:** As variáveis foram utilizadas para definir cores, fontes e outros valores que são usados em todo o site, facilitando a manutenção e a consistência do design.
    ```scss
    $primary-color: #007bff;
    $font-family: sans-serif;
    ```
*   ***Mixins:*** Os *mixins* foram utilizados para criar estilos reutilizáveis, como botões e formulários.
    ```scss
    @mixin button-style {
      background-color: $primary-color;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
    }

    button {
      @include button-style;
    }
    ```
*   ***Partials:*** Os *partials* foram utilizados para separar o código CSS em arquivos menores e mais fáceis de manter.
*   **Aninhamento:** O aninhamento foi utilizado para organizar o código CSS de forma mais clara e concisa.

## Como executar o projeto

1.  Clone o repositório: `git clone [URL do seu repositório]`
2.  Abra o arquivo `index.html` no seu navegador.

## Link do projeto

Você pode acessar o projeto online através do seguinte link: [calmaria-spa-web.vercel.app](https://calmaria-spa-web.vercel.app)

## Contribuições

Contribuições são sempre bem-vindas! Se você tiver alguma sugestão de melhoria ou encontrar algum bug, por favor, abra uma *issue* ou envie um *pull request*.

## Créditos

Este projeto foi desenvolvido com base nos conhecimentos adquiridos no curso "SASS e CSS: estilizando um site" da Alura, ministrado pelo instrutor Diego Carlos Martins Gayoso.