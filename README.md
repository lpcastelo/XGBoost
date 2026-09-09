# XGBoost
Aqui você irá encontrar a atividade do módulo 39 do curso de Cientista de Dados da Ebac.

A atividade consiste em aplicar o algoritmo XGBoost para desenvolver um modelo de classificação capaz de identificar quais clientes estão mais propensos a comprar carros.

Durante a atividade serão abordados temas como:

* Algoritmo XGBoost
* Classificação supervisionada
* Treinamento e avaliação de modelos
* Análise das variáveis preditoras
* Predição da propensão de compra de clientes
* Interpretação dos resultados obtidos

O objetivo é compreender o funcionamento do XGBoost e explorar seu potencial em problemas de classificação, utilizando um dos algoritmos mais eficientes e amplamente empregados em projetos de Machine Learning e Ciência de Dados.

## Dados

Base `CARRO_CLIENTES.csv` (1.000 clientes), com as variáveis `Gender`, `Age`, `AnnualSalary` e a variável alvo `Purchased` (compra do carro).

## Resultados

O modelo XGBoost (com `num_parallel_tree=5` e `max_leaves=10`) alcançou **88,5% de acurácia** no conjunto de teste, com precisão e recall próximos de 0,88–0,91 para ambas as classes. A importância de variáveis (`gain`) confirmou `Age` e `AnnualSalary` como os principais preditores, na mesma ordem indicada pela matriz de correlação — `Gender` teve importância bem menor.

## Tecnologias

- Python, pandas, numpy
- XGBoost
- scikit-learn (LabelEncoder, métricas)
- matplotlib, seaborn

## Como executar

1. Instale as dependências: `pip install pandas numpy xgboost scikit-learn matplotlib seaborn`.
2. Coloque `CARRO_CLIENTES.csv` no mesmo diretório do notebook.
3. Execute `Profissao Cientista de Dados M39 Projeto.ipynb` em ordem.
