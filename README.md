# Planejamento

## Objetivo:

Extrair os dados da bovespa e disponibilizar através de uma base de dados.

## Ativos de rede:

1. Servidor airbyte
2. Servidor dbt
3. Servidor airflow
4. Banco de dados Postgresql

## Etapas

1. Realizar extração dos arquivos do site
2. Realizar a carga em no schema raw_bovespa através do airbyte
3. Copiar a saída do airbyte para o servidor do dbt
4. Modelar os dados com o dbt
5. Desenvolver a documentação com o dbt
6. Desenvolver os testes com o dbt