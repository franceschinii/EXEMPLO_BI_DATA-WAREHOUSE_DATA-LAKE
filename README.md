# Projeto de Data Lake e Data Warehouse

Este projeto simula a criação de um Data Lake e um Data Warehouse utilizando Python, Pandas, SQL e outras bibliotecas relevantes. O objetivo é gerar, armazenar, analisar e visualizar conjuntos de dados aleatórios.

## Estrutura do Projeto

- **`data_lake.db`**: Banco de dados SQLite onde os dados do Data Lake são armazenados.
- **`data_warehouse.csv`**: Arquivo CSV que contém os dados consolidados do Data Warehouse.
- **`data_lake`**: Pasta que contém os arquivos CSV gerados com os dados do Data Lake.
- **`gerar_dados_lake.py`**: Script Python para gerar dados aleatórios e armazená-los no Data Lake.
- **`analise_dados_lake.py`**: Script Python para carregar os dados do Data Lake, realizar análises e criar visualizações.
- **`gerar_dados_warehouse.py`**: Script Python para carregar os dados do Data Lake, transformá-los e carregá-los no Data Warehouse.
- **`README.md`**: Este arquivo, fornecendo uma visão geral do projeto e instruções básicas.

## Data Lake

O Data Lake é uma coleção de dados brutos e não processados, armazenados em sua forma original. Os scripts `gerar_dados_lake.py` e `analise_dados_lake.py` estão relacionados ao Data Lake.

### Gerar Dados do Data Lake (`gerar_dados_lake.py`)

Este script cria conjuntos de dados aleatórios e os armazena em arquivos CSV na pasta `data_lake`. Cada arquivo contém 1000 linhas de dados.

### Analisar Dados do Data Lake (`analise_dados_lake.py`)

Este script carrega os dados do Data Lake, realiza análises estatísticas e cria visualizações gráficas para explorar os dados brutos.

## Data Warehouse

O Data Warehouse é um sistema de armazenamento de dados organizado e otimizado para análises e consultas. Os scripts `gerar_dados_warehouse.py` estão relacionados ao Data Warehouse.

### Gerar Dados do Data Warehouse (`gerar_dados_warehouse.py`)

Este script carrega os dados do Data Lake, realiza transformações e carrega os dados no Data Warehouse, criando um arquivo CSV chamado `data_warehouse.csv`.

## Como Executar

1. Certifique-se de ter o Python e as bibliotecas necessárias instaladas (`pandas`, `matplotlib`, `seaborn`, `sqlalchemy`).
2. Execute o script `gerar_dados_lake.py` para gerar os dados brutos do Data Lake.
3. Execute o script `analise_dados_lake.py` para realizar análises e visualizações nos dados do Data Lake.
4. Execute o script `gerar_dados_warehouse.py` para transformar e carregar os dados do Data Lake no Data Warehouse.
