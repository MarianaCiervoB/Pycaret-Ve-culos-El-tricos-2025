Este repositório contém um projeto de **Machine Learning** focado na análise e previsão do crescimento da frota de veículos elétricos por município. Utilizando a biblioteca **PyCaret**, o projeto automatiza a comparação de modelos de regressão para encontrar a melhor precisão nos dados de 2025 (`dados_VEs_porMunicipio2025`).

O objetivo principal é processar dados históricos de frotas para prever a tendência de adoção de veículos sustentáveis. O projeto abrange desde o tratamento inicial dos dados até a avaliação de métricas de desempenho de modelos preditivos.

### Estrutura do Notebook

1. **Tratamento de Dados**: Limpeza de colunas como `Cod_municipio`;
2. **Análise de Dados**: Organização de séries temporais ou geográficas;
3. **AutoML com PyCaret**: 
    - Setup do ambiente de regressão;
    - Comparação de modelos (Random Forest, XGBoost, CatBoost, etc.);
    - Otimização de hiperparâmetros;
4. **Visualização**: Gráficos de erro residual e importância de variáveis;

## Bibliotecas

* **Python 3.13**
* **Pandas**
* **PyCaret 3.4**
* **Scikit-Learn**

## Como Executar o Código Localmente

### 1. Requisitos Prévios
Certifique-se de ter o Python instalado e o arquivo de dados `dados_VEs_porMunicipio2025.csv` na pasta correta.

### 2. Instalação
No seu terminal ou em uma célula do notebook, instale as dependências:
```bash
pip install pandas pycaret
```
### 3. Requisitos Prévios
Altere o caminho do arquivo `dados_VEs_porMunicipio2025.csv` na linha: caminho = r"C:\Caminho\Para\Seu\Arquivo.csv"
