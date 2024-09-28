# Projeto de Scraping e Análise de Livros - Estante Virtual

## Descrição

Este projeto realiza o scraping de dados de livros do site **Estante Virtual** usando a biblioteca **Selenium** para automação do navegador. O código percorre automaticamente as páginas do site, coletando informações sobre os livros, como:

- Nome do livro
- Preço
- Autor
- Editora
- Ano de publicação

Os dados extraídos são armazenados em um **DataFrame** com o auxílio do **Pandas** para posterior análise. Além disso, utilizei **Plotly** para gerar visualizações interativas e facilitar a compreensão dos padrões presentes nos dados.

## Funcionalidades

- **Scraping automatizado**: O código navega por várias páginas do site da Estante Virtual, coletando as informações de cada livro de maneira automática.
- **Armazenamento em DataFrame**: As informações dos livros são organizadas em um DataFrame para facilitar a manipulação e análise dos dados.
- **Análise de dados**: Posteriormente, é realizada uma análise para identificar padrões nos livros, como autores mais frequentes, editoras predominantes, preço dos livros e anos de publicação.

### Exemplos de Resultados

Alguns dos resultados obtidos incluem:

- Identificação de autores com mais publicações.
- Editoras predominantes entre os livros analisados.
- Exemplos de livros com preços mais altos.

### Relatório Final

Um **relatório completo** com todos os detalhes da análise é gerado ao final do processo, oferecendo uma visão aprofundada dos padrões encontrados. Confira o relatório final para mais informações sobre os autores, editoras, preços e anos de publicação dos livros analisados.

## Bibliotecas Utilizadas

- **Pandas**: Utilizado para criar e manipular a base de dados em formato de DataFrame.
- **Plotly**: Usado para criar visualizações interativas dos dados extraídos.
- **Selenium**: Ferramenta principal para automação e scraping das informações do site.
- **WebDriver (Chrome)**: Utilizado para conectar o código ao navegador Chrome e permitir a automação do processo de navegação.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Sugestões e melhorias são bem-vindas!





