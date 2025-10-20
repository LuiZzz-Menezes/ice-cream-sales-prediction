
# PrevisaoSorvetes
# Prevendo Vendas de Sorvete com Azure ML e MLflow

## Visão Geral do Projeto
Este projeto tem como objetivo prever a quantidade de vendas de sorvete com base em dados históricos de temperatura e preço. Utilizando **Python** com **Azure Machine Learning (Azure ML)** para construir e registrar um modelo de regressão.

  ## 📌 Pastas
- **`data/`**: Contém o arquivo de dados `tabela_sorvete.xlsx`.
- **`inputs/`**: Contém as sentenças
- **`imagens/`**: Contém as imagens do processo


---

## 🚀 **Processo**
### 1️⃣ **Configuração do ambiente no Azure ML**
1. Criei um workspace no **Azure Machine Learning**.
2. Subi o arquivo de dados (`Ice Cream.csv`) para o workspace.

### 2️⃣ **Treinamento do Modelo**
1. Separei os dados em **treino** e **teste** usando `train_test_split`.
2. Treinei um modelo de **regressão linear** com `LinearRegression()`.
3. Avaliei o modelo com o **erro quadrático médio (MSE)**.


## 🔍 **Insights Obtidos**
🔹 **Importância da Limpeza dos Dados**: Pequenos erros, como colunas com espaços extras ou caracteres especiais, podem impedir a execução do código.

🔹 **Uso do MLflow**: Útil para versionar experimentos e comparar modelos.

🔹 **Integração com Azure ML**: O pipeline fica mais escalável, permitindo monitorar experimentos em tempo real.
