# 🧠 1001-Experiments – Data Engineer Practical Exam

Este repositório contém a solução para o desafio prático de engenharia de dados da empresa fictícia **1001-Experiments**, que desenvolve suplementos personalizados com base em dados de saúde coletados por dispositivos vestíveis e hábitos diários.

---

## 🧪 Objetivo

Integrar e limpar quatro conjuntos de dados distintos para gerar uma visão unificada da saúde, suplementação e perfil dos usuários.

---

## 📁 Arquivos do projeto

- `1001_experiments.ipynb`: notebook com a função `merge_all_data()` que realiza todo o processamento.
- `user_health_data.csv`, `supplement_usage.csv`, `experiments.csv`, `user_profiles.csv`
- `README.md`: este arquivo com instruções e explicações do projeto.

---

## 🚀 Como executar

1. Certifique-se de ter os quatro arquivos `.csv` no mesmo diretório do notebook.
2. Execute o notebook `1001_experiments.ipynb`.
3. A função principal pode ser chamada assim:

```python
df = merge_all_data(
    'user_health_data.csv',
    'supplement_usage.csv',
    'experiments.csv',
    'user_profiles.csv'
)

print(df.head())
