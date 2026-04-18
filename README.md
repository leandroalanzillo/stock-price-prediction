# 📈 Stock Price Prediction with NeuralProphet

Previsão de preços de ações utilizando inteligência artificial com o modelo NeuralProphet, desenvolvido pelo Meta. O projeto aplica técnicas de aprendizado de máquina em séries temporais para prever tendências futuras de ativos financeiros.

---

## 🎯 Objetivo

Treinar um modelo de IA capaz de aprender o comportamento histórico de uma ação e prever sua tendência para os próximos 365 dias úteis, com base em dados reais do mercado financeiro.

---

## 🗂️ Estrutura do Projeto

```
stock-price-prediction/
│
├── main.ipynb        # Notebook principal com todo o pipeline
└── README.md
```

---

## 🔄 Pipeline do Projeto

```
1. Importação de bibliotecas
        ↓
2. Download dos dados históricos (yfinance)
        ↓
3. Formatação dos dados (colunas ds e y)
        ↓
4. Treinamento do modelo (NeuralProphet)
        ↓
5. Geração de previsões futuras
        ↓
6. Avaliação do modelo (R², MAE, MAPE)
        ↓
7. Visualização dos resultados (matplotlib)
```

---

## 🧰 Tecnologias Utilizadas

| Biblioteca | Finalidade |
|---|---|
| `neuralprophet` | Modelo de IA para séries temporais |
| `yfinance` | Download de dados históricos do Yahoo Finance |
| `pandas` | Manipulação e formatação dos dados |
| `matplotlib` | Visualização dos resultados |
| `scikit-learn` | Métricas de avaliação do modelo |
| `torch` | Backend de deep learning |

---

## ⚙️ Como Executar

### Pré-requisitos

- Python 3.11 (recomendado — versões mais recentes podem ter incompatibilidades com o NeuralProphet)

### 1. Clone o repositório

```bash
git clone https://github.com/leandroalanzillo/stock-price-prediction.git
cd stock-price-prediction
```

### 2. Crie e ative um ambiente virtual

```bash
python3.11 -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

### 3. Instale as dependências

```bash
pip install neuralprophet yfinance matplotlib scikit-learn pandas
```

### 4. Execute o notebook

Abra o `main.ipynb` no VS Code ou Jupyter e execute todas as células com **Run All**.

> ⚠️ **Atenção:** Se estiver usando PyTorch 2.6+, é necessário aplicar um patch de compatibilidade com o NeuralProphet. Ele já está incluído na célula de treinamento do notebook.

---

## 📊 Exemplo de Resultado

O modelo foi treinado com dados históricos da **Petrobras (PETR4)** de 2015 a 2025 e gerou previsões para os próximos 365 dias úteis, identificando a tendência de alta e os padrões de sazonalidade ao longo do ano.

---

## 📐 Métricas de Avaliação

| Métrica | Descrição |
|---|---|
| **R²** | Percentual da variância explicada pelo modelo (quanto mais próximo de 1, melhor) |
| **MAE** | Erro absoluto médio em valor monetário |
| **MAPE** | Erro percentual médio em relação ao preço real |

---

## ⚠️ Aviso

Este projeto tem finalidade **exclusivamente educacional**. As previsões geradas pelo modelo **não constituem recomendação de investimento**. O mercado financeiro envolve riscos e nenhum modelo garante resultados futuros.

---

## 🔗 Acesse

<div align="center">

[![Ver Repositório](https://img.shields.io/badge/-%20VER%20REPOSITÓRIO-black?style=for-the-badge&logo=github)](https://github.com/leandroalanzillo/stock-price-prediction)
[![Ver Notebook](https://img.shields.io/badge/-%20VER%20NOTEBOOK-orange?style=for-the-badge&logo=jupyter)](https://github.com/leandroalanzillo/stock-price-prediction/blob/main/main.ipynb)
[![LinkedIn](https://img.shields.io/badge/-LINKEDIN-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/leandrolanzillo)

</div>
