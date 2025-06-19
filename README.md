# 1001-Experiments – Data Engineer Practical Exam

Este repositório contém a solução para o desafio prático de engenharia de dados da empresa fictícia **1001-Experiments**, que desenvolve suplementos personalizados com base em dados de saúde.

## 🧪 Objetivo

Unificar e limpar quatro conjuntos de dados distintos para fornecer uma visão integrada da saúde, suplementação e perfil dos usuários.

## 📁 Arquivos

- `suplementos_e_experimentos.ipynb`: função `merge_all_data()` que realiza todo o processamento.
- `user_health_data.csv`, `supplement_usage.csv`, `experiments.csv`, `user_profiles.csv`
- `README.md`: documentação.

## 🚀 Como executar

```python
from merge_data import merge_all_data

df = merge_all_data('user_health_data.csv', 'supplement_usage.csv', 'experiments.csv', 'user_profiles.csv')
print(df.head())
