# Planejamento

## Objetivo:

Extrair os dados da bovespa e disponibilizar através:
1. Data Warehouse
2. Rest API
3. Local Python Library

## Ativos de rede

1. Servidor Airbyte
2. Servidor dbt
3. Servidor Airflow
4. Servidor Fastapi
5. Banco de Dados Postgresql

## Etapas

1. Realizar extração dos arquivos do site
2. Realizar a carga em no schema raw_bovespa através do airbyte

### Data Warehouse
3. Copiar a saída do airbyte para o servidor do dbt
4. Modelar os dados com o dbt
5. Disponibilizar a documentação com o dbt
6. Disponibilizar os testes com o dbt

### Rest API
7. Sobre os dados modelados, implementar Rest API através do Fastapi

### Local Python Library
8. Sobre os dados modelados, implementar Local Python Library