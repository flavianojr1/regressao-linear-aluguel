
# 📊 Regressão Linear Simples e Múltipla — Exercício Prático

Este repositório contém a resolução do exercício prático da Módulo 18 do curso **Profissão: Cientista de Dados** (EBAC), focado em regressão linear simples e múltipla usando Python e a biblioteca `scikit-learn`.

## 🧠 Objetivo

Comparar modelos de regressão linear simples e múltipla com base no coeficiente de determinação R², avaliando desempenho em dados de treino e teste.

## 📂 Arquivos

- `Profissao Cientista de Dados M18 Pratique.ipynb` — Notebook com todo o código e explicações.
- `ALUGUEL_MOD12.csv` — Arquivo contendo os dados da análise.
- `README.md` — Este arquivo.

## ⚙️ Tecnologias utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 📈 Principais Resultados

| Modelo                   | R² Treino | R² Teste |
|--------------------------|-----------|----------|
| Regressão Linear Simples | ~0.500    | ~0.514   |
| Regressão Linear Múltipla| 0.577     | 0.5968   |

O modelo de regressão múltipla apresentou melhor desempenho, explicando uma proporção maior da variabilidade da variável-alvo e com boa generalização.

## 💡 Conclusão

A inclusão de variáveis adicionais no modelo múltiplo contribuiu para um aumento no R² e, portanto, melhor capacidade de explicação. A consistência entre treino e teste indica que o modelo está bem ajustado, sem sinais de overfitting.

---

> Projeto desenvolvido como parte do curso da EBAC.
