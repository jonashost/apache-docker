# Projeto Apache com Docker Compose

Este projeto executa um servidor Apache rodando em container Docker usando Docker Compose. A aplicação é uma página web simples com HTML, CSS e JavaScript.

## Estrutura do projeto

- `docker-compose.yml`: arquivo de configuração do Docker Compose para subir o container Apache.
- `website/`: pasta com arquivos da aplicação web (HTML, CSS, JS).

## Como executar

1. Tenha o Docker e Docker Compose instalados.
2. No terminal, navegue até a pasta do projeto.
3. Execute o comando para subir o container:

```bash
docker-compose up -d
