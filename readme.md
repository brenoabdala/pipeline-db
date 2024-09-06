### Dados de Voos de NYC para SQLite

Este projeto é responsável pela leitura, tratamento e inclusão dados em um banco SQLlite. O CSV  contém informações sobre voos que partiram de Nova York.

O Projeto foi realizado em aula(Python for Data Engenieer), pelo MBA de engenharia de dados da faculdade Impacta, ministrado pela professora Carolina.

## Índice

1. [Funcionalidades](#funcionalidades)
2. [Estrutura do Projeto](#estrutura-do-projeto)

## Funcionalidades

- Ler dados de voos de um arquivo CSV (`nycflights.csv`).
- Validar as colunas do dataframe conforme o arquivo work_metadado_flights.xlsx.
- Tratamento e enriquecimento dos dados.
- Cria um banco de dados SQLite e tabela(s) para armazenar os dados dos voos.
- Insere os dados dos voos no banco de dados SQLite.

## Estrutura do Projeto

```bash
├── README.md         # Documentação do projeto
├──assets
    └── utils.py                   # Script Python com funções auxiliares para o app.py
    └── create_table.py            # Script Python para criação da tabela nyflights no banco NyflightsDb
    └── work_metadado_flights.xlsx # Arquivo xlsx com metadados do banco NyflightsDb
├──data
    └── NyflightsDB.db # Banco de dados SQLite (gerado após rodar o script)
├── .env               # Arquivo de configuração com variáveis de ambiente
├── requirements.txt   # Dependências Python
└── app.py             # Script principal para leitura, tratamento e inserção de dados no SQL Lite

```
