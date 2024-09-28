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
- **Análise de dados**: Posteriormente, é realizada uma análise para identificar padrões nos livros, como autores mais frequentes, editora predominante, preço do livro mais caro e ano de publicação mais comum.

### Principais Resultados da Análise

1. **Autores mais frequentes**:
   - Antje Damm: 5 livros
   - Murilo Badaró: 4 livros
   - Drauzio Varella: 3 livros
   - Lilia Moritz Schwarcz: 3 livros

2. **Editora predominante**:
   - **Claro Enigma** é responsável por 90% dos livros analisados.

3. **Livro mais caro**:
   - "O Maior de Todos os Mistérios" da editora **Claro Enigma**, custando **R$ 332,82**.

4. **Ano predominante**:
   - A maioria dos livros foi publicada no ano de **2011**.

### Relatório Final

Ao final do arquivo de análise, um **relatório** é gerado contendo um resumo das informações extraídas do scraping. Esse relatório inclui os principais resultados sobre autores, editoras, preços e anos de publicação dos livros.

## Bibliotecas Utilizadas

- **Pandas**: Utilizado para criar e manipular a base de dados em formato de DataFrame.
- **Plotly**: Usado para criar visualizações interativas dos dados extraídos.
- **Selenium**: Ferramenta principal para automação e scraping das informações do site.
- **WebDriver (Chrome)**: Utilizado para conectar o código ao navegador Chrome e permitir a automação do processo de navegação.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Sugestões e melhorias são bem-vindas!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).


