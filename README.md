# MVP Machine Learning – Classificação de Vendas

## Objetivo

Desenvolver um modelo de Machine Learning capaz de classificar vendas em três categorias:

* Venda Baixa
* Venda Média
* Venda Alta

A classificação é realizada a partir de características do produto e do contexto da venda, como categoria, marca, preço, país, continente e período da venda.

---

## Problema

Trata-se de um problema de **Aprendizado Supervisionado do tipo Classificação Multiclasse**.

Variável alvo:

* ClasseVenda

Classes:

* Venda Baixa
* Venda Média
* Venda Alta

---

## Dataset

O conjunto de dados contém informações de vendas, incluindo:

* Produto
* Categoria
* Preço Unitário
* Custo Unitário
* Marca
* Quantidade Vendida
* Faturamento
* Nome do Cliente
* País
* Continente
* Data da Venda

Foram criadas as variáveis:

* MesVenda
* AnoVenda

---

## Principais etapas

1. Limpeza e preparação dos dados
2. Análise exploratória (EDA)
3. Engenharia de atributos
4. Divisão treino/teste (80/20)
5. Pré-processamento com Pipeline
6. Treinamento de modelos
7. Otimização de hiperparâmetros
8. Avaliação final

---

## Modelos avaliados

* Baseline (DummyClassifier)
* Logistic Regression
* Random Forest
* Random Forest Otimizada

---

## Resultados

| Modelo                  | F1 Weighted |
| ----------------------- | ----------- |
| Baseline                | 0.456       |
| Logistic Regression     | 0.459       |
| Random Forest           | 0.545       |
| Random Forest Otimizada | 0.340       |

O melhor modelo foi a **Random Forest**, apresentando o maior F1-score ponderado e melhor equilíbrio entre as classes.

---

## Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab

---

## Autor

Márcio Miranda

Projeto desenvolvido como MVP para a disciplina de Machine Learning da Pós-Graduação em Ciência de Dados.

Acessar Projeto: <kbd>Abrir no Colab (https://colab.research.google.com/github/marciomalrj/MVPML/blob/main/MVP_Machine_Learning.ipynb)</kbd>
