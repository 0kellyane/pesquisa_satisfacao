
markdown
Copiar
Editar
# 🎬 Pesquisa de Satisfação – Cine Biblioteca Maria Dolores

Este repositório apresenta a análise de dados de uma **pesquisa de satisfação** realizada no **Cine Biblioteca**, projeto da **Biblioteca Comunitária Maria Dolores**, entre os anos de **2024 e 2025**, com a participação de **152 pessoas** da comunidade.

---

## 📌 Objetivo

Analisar a experiência do público com relação à frequência ao cinema e à recomendação do espaço para amigos ou familiares.

---

## 🧰 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) – manipulação de dados
- [Matplotlib](https://matplotlib.org/) – visualização gráfica
- [NumPy](https://numpy.org/) – suporte matemático

---

## 🗂️ Etapas do Projeto

### 📥 1. Importação das Bibliotecas

As bibliotecas `pandas`, `matplotlib.pyplot` e `numpy` foram utilizadas para manipular os dados e criar gráficos informativos.

### 🧾 2. Organização dos Dados

Os dados da pesquisa foram organizados em um `DataFrame` com a seguinte estrutura:

| Resposta         | Você já frequentou um cinema? | Você recomendaria para seus amigos ou familiares? |
|------------------|-------------------------------|---------------------------------------------------|
| sim              | 124                           | 140                                               |
| não              | 20                            | 4                                                 |
| não responderam  | 9                             | 9                                                 |

### 📊 3. Visualização com Gráfico de Barras

Foi criado um **gráfico de barras lado a lado** com as respostas das duas perguntas principais:

- **Você já frequentou um cinema?**
- **Você recomendaria para seus amigos ou familiares?**

Cada grupo de barras representa as categorias: **"sim"**, **"não"** e **"não responderam"**.

---

## 📈 Resultados

A análise demonstrou:

- ✅ **Alta aceitação do projeto**:  
  - 124 pessoas afirmaram já ter frequentado o cinema.
  - 140 pessoas recomendariam o Cine Biblioteca para outros.

- ❗ **Baixo índice de rejeição e omissão**:  
  - Apenas 20 disseram que nunca frequentaram.
  - Apenas 4 disseram que não recomendariam.
  - 9 pessoas não responderam a cada pergunta.
