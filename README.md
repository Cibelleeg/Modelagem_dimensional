# Modelagem_dimensional
Este repositório contém a modelagem de dados dimensional baseada em uma fact table (tabela de fatos), utilizada para análise e tomada de decisões em um ambiente de Business Intelligence (BI).
O notebook realiza a leitura, tratamento e análise de dados de vendas, aplicando conceitos de modelagem dimensional para explorar os dados de forma eficiente.

# 1. Estrutura do Projeto
O projeto está organizado da seguinte forma:

📂 Data_content/ → Pasta onde o arquivo CSV de dados de vendas será armazenado.
📜 Modelagem_dimensional.ipynb → Notebook principal com todo o código para leitura, tratamento e análise dos dados.

# 2. Funcionalidades Implementadas
##  2.1 Leitura de Arquivos
        O notebook verifica e garante que o arquivo de dados está na pasta correta.
        Se o arquivo não estiver no diretório esperado, o usuário é instruído a fazer o upload.
        
##  2.2 Exploração e Tratamento de Dados
        Exibição de informações gerais do DataFrame (número de linhas, colunas e tipos de dados).
        Tratamento de dados para garantir a consistência antes da análise.

##  2.3 Visualização de Dados
        Geração de gráficos utilizando Matplotlib e Seaborn para explorar tendências e padrões nas vendas.
        
##  2.4 Exportação de Dados
        Salvamento do DataFrame tratado no formato Parquet, garantindo eficiência no armazenamento e leitura posterior.

# 3. Dependências Necessárias
As seguintes bibliotecas são utilizadas no projeto:

    - pandas → Manipulação de dados
    - matplotlib → Visualização de gráficos
    - seaborn → Análises gráficas aprimoradas
    - geopy → Obtenção de coordenadas geográficas (latitude/longitude)
    - pyarrow e fastparquet → Manipulação de arquivos Parquet

##  3.1 Instalação das Dependências
    Para instalar todas as dependências, execute no terminal:
        - <pip install pandas matplotlib seaborn geopy pyarrow fastparquet>

