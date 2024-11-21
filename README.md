# web_crawling_ex

# GitHub Trending Projects Scraper)
            Este repositório contém um script Python que realiza web crawling na página de **GitHub Trending** para extrair informações sobre os 10 projetos mais populares.

## Conteúdo

- **github_scraper.py**: Script Python para extrair informações e salvar os dados em um arquivo CSV.
- **github.csv**: Arquivo de saída contendo os dados extraídos, no formato delimitado por `;`.

## Funcionalidades

O script realiza as seguintes operações:
1. Acessa a página [GitHub Trending](https://github.com/trending).
2. Extrai informações como ranking, nome do projeto, linguagem, estrelas, estrelas do dia e forks.
3. Salva os dados no arquivo `github.csv`.

## Dependências

Certifique-se de instalar as seguintes bibliotecas antes de executar o código:
- `requests`
- `BeautifulSoup` (parte do `bs4`)
