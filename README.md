# 🤖 Trabalho Prático AV1 — Machine Learning

Projeto acadêmico desenvolvido para a disciplina de **Machine Learning**, com o objetivo de aplicar técnicas de análise exploratória, pré-processamento de dados, treinamento de modelos e interpretação de resultados em diferentes problemas.

## 🎯 Objetivo

Explorar diferentes abordagens de aprendizado de máquina para resolver problemas práticos, documentando as etapas de preparação dos dados, aplicação dos algoritmos e análise dos resultados obtidos.

## 👥 Equipe

- Gean Carlos
- Liedson Araujo
- Luiz Henrique
- Erick William

## 📚 Problemas propostos

O trabalho é composto por quatro problemas:

| Problema | Tema | Abordagem |
|---|---|---|
| 1 | Regressão Linear — O Preço Justo | Aprendizado supervisionado |
| 2 | Classificação — A Ameaça do Churn | Aprendizado supervisionado |
| 3 | Clusterização — O Perfil do Consumidor | Aprendizado não supervisionado |
| 4 | Clusterização Musical — Criando a Playlist Perfeita | Aprendizado não supervisionado |

## 🏠 Problema 1 — Regressão Linear: O Preço Justo

O objetivo é construir um modelo de regressão para estimar preços de imóveis a partir de características presentes na base de dados.

Nesta etapa, são explorados:

- Análise exploratória dos dados e das correlações;
- Tratamento de valores ausentes;
- Conversão de variáveis categóricas em atributos numéricos;
- Divisão dos dados em conjuntos de treino e teste;
- Treinamento de um modelo de Regressão Linear;
- Avaliação do desempenho por meio de métricas de regressão.

## 🛍️ Problema 3 — Clusterização: O Perfil do Consumidor

O objetivo é segmentar clientes de um shopping em cinco grupos com base na **renda anual** e na **pontuação de gastos (Spending Score)**, identificando perfis de consumo sem utilizar rótulos previamente definidos.

Nesta etapa, são explorados:

- Padronização das variáveis com `StandardScaler`;
- Método do Cotovelo para avaliar o número de clusters;
- Coeficiente de silhueta como métrica complementar;
- Treinamento do algoritmo K-Means com cinco clusters;
- Visualização e interpretação dos agrupamentos;
- Sugestões de ações de marketing para os perfis identificados.

A idade e outras colunas que não fazem parte das duas variáveis selecionadas não são utilizadas no treinamento do modelo.

## 🎵 Problema 4 — Clusterização Musical: Criando a Playlist Perfeita

O objetivo é agrupar músicas com base em suas características sonoras, buscando identificar grupos que possam representar playlists com características semelhantes.

Nesta etapa, são explorados:

- Limpeza e preparação dos dados;
- Análise da correlação entre energia (`energy`) e acústica (`acousticness`);
- Pré-processamento de variáveis numéricas e categóricas;
- Aplicação do algoritmo K-Means com cinco clusters;
- Análise dos grupos e interpretação das músicas agrupadas.

O gênero musical cadastrado (`track_genre`) não é utilizado como variável de entrada do modelo, para que os agrupamentos sejam formados a partir das características musicais selecionadas.

## 🛠️ Tecnologias e ferramentas

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git e GitHub

## 📁 Estrutura do repositório

```text
AV1-Machine-Learning/
├── .gitignore
├── README.md
├── notebooks/
│   ├── problema_1.ipynb
│   ├── problema_2.ipynb
│   ├── problema_3.ipynb
│   └── problema_4.ipynb
├── datasets/
└── relatorios/
    ├── Relatorio_Problema_3.pdf
    └── Relatorio_Problema_4.pdf
```

> A estrutura acima representa a organização prevista para os materiais do trabalho. Os arquivos dos problemas 1 e 2, assim como os datasets, devem estar presentes no repositório conforme forem finalizados e disponibilizados pela equipe.

## 📌 Entregáveis

- Notebooks com código, análises e resultados dos quatro problemas;
- Relatórios com a descrição da metodologia, os principais resultados e suas interpretações;
- Discussão dos resultados e das limitações dos modelos utilizados.

---

**Trabalho acadêmico — Machine Learning | AV1 — 2026**
