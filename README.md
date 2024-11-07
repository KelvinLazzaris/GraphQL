# Consulta de Países

Este projeto é uma aplicação simples que utiliza Flask e HTML para consultar e exibir uma lista de países com seus respectivos emojis de bandeira. A aplicação consome dados de uma API GraphQL de países e os exibe na interface do usuário.

## Funcionalidades

- Interface web para consulta de países.
- Consulta realizada através de uma API GraphQL, que retorna uma lista de países com seus nomes e bandeiras (em formato de emoji).
- Estilização básica e animações para uma experiência visual agradável.

## Tecnologias Utilizadas

- **Flask**: Framework em Python para o desenvolvimento do back-end.
- **HTML/CSS**: Interface web.
- **JavaScript**: Manipulação da DOM e integração com a API.
- **GraphQL**: A consulta é realizada utilizando o padrão GraphQL para obter informações sobre os países.

## Estrutura do Projeto

- `app.py`: Contém o código back-end em Flask, responsável por:
  - Renderizar a página principal (`index.html`).
  - Realizar a requisição à API GraphQL e retornar os dados dos países.

- `index.html`: Contém o código front-end, que:
  - Exibe o título e o botão de consulta.
  - Mostra os países e suas bandeiras após a consulta.

## Como Executar

1. **Pré-requisitos**:
   - Python 3.x instalado.
   - Bibliotecas Flask e requests instaladas (`pip install flask requests`).

2. **Iniciar a aplicação**:
   - Clone o repositório e navegue até o diretório do projeto.
   - Execute o arquivo `app.py` com o seguinte comando:
     ```bash
     python app.py
     ```
   - Acesse a aplicação no navegador pelo endereço `http://127.0.0.1:5000`.

3. **Uso**:
   - Na página principal, clique no botão "Clique aqui para vê-los" para ver a lista de países e suas bandeiras.

## Exemplo de API Utilizada

A API GraphQL utilizada neste projeto está disponível em `https://countries.trevorblades.com/`. Ela fornece dados de países, incluindo nome e bandeira, que são exibidos na aplicação.

## Estilização e Animações

- A página apresenta um título animado com efeito de opacidade.
- O botão "Clique aqui para vê-los" muda de cor ao passar o mouse, proporcionando uma experiência interativa.

## Contribuições

Contribuições são bem-vindas! Para contribuir, faça um fork deste repositório, crie uma nova branch com sua feature/correção e abra um Pull Request.

---

**Licença**: Este projeto está sob a licença MIT.
