
## Challenge_2_Telecom X_análise de evasão de clientes

Este projeto tem como objetivo analisar o comportamento dos clientes de uma empresa de telecomunicações e desenvolver estratégias para reduzir a evasão (churn). Foram aplicadas técnicas de análise exploratória, visualização de dados e modelagem preditiva para identificar padrões, extrair percepções relevantes e propor soluções práticas voltadas à retenção.

---

## Objetivo

- Identificar padrões associados ao cancelamento de clientes.
- Analisar variáveis que impactam a taxa de churn.
- Desenvolver modelos preditivos para antecipar a evasão.
- Propor estratégias de retenção fundamentadas em dados concretos.

---

## Organização do Projeto

```text
TelecomX_BR/
│
├── TelecomX_BR.ipynb          # Notebook principal com todo o pipeline de análise
├── data/                      # Pasta com o dataset original e transformado
│   └── telecom_customers.csv
├── images/                    # Gráficos gerados durante a análise
├── README.md                  # Este arquivo
└── requirements.txt           # Lista de dependências
```

---

## Setup e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/TelecomX_BR.git
cd TelecomX_BR
```

### 2. Instale as dependências

Recomenda-se o uso de um ambiente virtual:

```bash
pip install -r requirements.txt
```

Se estiver utilizando o Google Colab, basta abrir o notebook e executar as células em sequência.

---

## Ciclo de Execução do Projeto

### Extração
- Leitura do dataset `telecom_customers.csv`.

### Transformação
- Tratamento de valores nulos e correção de inconsistências nos dados.
- Padronização de variáveis categóricas e numéricas para uniformidade e consistência analítica.

### Análise
- Criação de visualizações por meio de gráficos de barras, boxplots e histogramas.
- Identificação de variáveis com maior correlação com o churn.

### Modelagem
- Avaliação de modelos como Random Forest, XGBoost e Regressão Logística.
- Preparação e engenharia de dados para aplicação de algoritmos de machine learning.

### Relatório Final
- Apresentação de percepções estratégicas para retenção de clientes.
- Proposição de campanhas direcionadas e melhorias nos serviços com base nos resultados obtidos.

---

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

---

## Riscos e Vulnerabilidades

- Dados faltantes: Algumas colunas apresentam valores nulos que podem impactar a análise.
- Desequilíbrio de classes: A baixa ou alta proporção de churn em relação ao total de clientes pode comprometer o desempenho dos modelos.
- Overfitting: Modelos excessivamente complexos podem se ajustar de forma exagerada aos dados de treino, reduzindo a capacidade de generalização.


