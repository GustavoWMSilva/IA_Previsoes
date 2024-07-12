# README.md

## Análise e Previsão de Score de Crédito

Este repositório contém a implementação de um modelo de aprendizado de máquina para prever o score de crédito de clientes com base em seus dados demográficos e históricos. Dois algoritmos foram utilizados: Random Forest e K-Nearest Neighbors (KNN). 

### Estrutura do Projeto

O projeto está dividido nos seguintes blocos:

1. **Carregar Dados**
2. **Tratar Dados**
3. **Separar Dados**
4. **Treinar Modelos**
5. **Previsões**
6. **Previsão para Novos Clientes**
7. **Importância das Características**

### Descrição dos Blocos

#### Bloco 1: Carregar Dados
Carrega os dados dos clientes a partir de um arquivo CSV chamado `clientes.csv`. Exibe uma amostra dos dados e informações sobre o dataset.

#### Bloco 2: Tratar Dados
Converte colunas categóricas em valores numéricos usando `LabelEncoder`, exceto a coluna `score_credito` que é o alvo da previsão.

#### Bloco 3: Separar Dados
Separa os dados em variáveis dependentes (`x`) e independentes (`y`). Em seguida, divide os dados em conjuntos de treino e teste com 70% dos dados para treino e 30% para teste.

#### Bloco 4: Treinar Modelos
Treina dois modelos de aprendizado de máquina: Random Forest e KNN, utilizando os dados de treino.

#### Bloco 5: Previsões
Realiza previsões utilizando ambos os modelos no conjunto de teste. Calcula e exibe a acurácia de cada modelo.

#### Bloco 6: Previsão para Novos Clientes
Carrega dados de novos clientes a partir de um arquivo CSV chamado `novos_clientes.csv`, realiza as mesmas transformações de dados e faz previsões utilizando o modelo de Random Forest treinado.

#### Bloco 7: Importância das Características
Calcula e exibe a importância de cada característica para o modelo de Random Forest, ajudando a entender quais características são mais relevantes para a previsão do score de crédito.

### Resultados

Os resultados incluem:
- Acurácia dos modelos Random Forest e KNN no conjunto de teste.
- Previsões de score de crédito para novos clientes.
- Importância das características utilizadas no modelo Random Forest.

### Como Executar

1. **Requisitos**:
   - Python 3.x
   - Bibliotecas: pandas, numpy, scikit-learn

2. **Passos**:
   - Coloque os arquivos `clientes.csv` e `novos_clientes.csv` no diretório do projeto.
   - Execute o script Python para carregar, tratar os dados, treinar os modelos, fazer previsões e exibir os resultados.

### Contato

Para mais informações, entre em contato com os desenvolvedores.

---

Este trabalho foi realizado como parte de um desenvolvimento profissional.
