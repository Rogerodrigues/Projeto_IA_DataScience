# 📊 Projeto: IA aplicada a Data Science - Visualização de Dados com Python

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

## 🧑‍🎓 Sobre o Projeto

Este projeto faz parte do meu processo de aprendizagem em **Ciência de Dados**. Aqui, utilizei **Python**, **Pandas** e ferramentas de **Visualização de Dados** para resolver um desafio fictício de análise de vendas de uma empresa chamada **Zoop**, um grande e-commerce brasileiro.

Além disso, tive o apoio da **IA (ChatGPT)** durante a construção das análises e dos gráficos 📈.

---

## 🏢 Cenário do Projeto

A **Zoop** é uma varejista nacional que vende seus produtos online e precisa entender melhor o comportamento dos seus clientes e o faturamento durante o ano de 2023.

Como **Analista de Dados Júnior em formação**, meu papel foi:

✅ Importar os dados do e-commerce da Zoop  
✅ Realizar uma **Análise Exploratória de Dados (EDA)**  
✅ Construir **visualizações com foco no público e nas vendas**  
✅ Utilizar a **IA (ChatGPT)** como suporte nas análises  

---

## 📌 Dados Utilizados

Foram utilizadas duas bases de dados principais (disponíveis publicamente no GitHub da Alura):

- **Clientes da Zoop** (dados demográficos por compra)
- **Vendas da Zoop em 2023** (detalhes de faturamento por compra)

---

## 🚀 Ferramentas e Tecnologias

- **Python 3**
- **Pandas**
- **Seaborn / Matplotlib**
- **Google Colab**
- **Jupyter Notebook**
- **ChatGPT (como assistente nas análises)**

---

## 🎯 Perguntas Respondidas no Projeto

Durante o projeto, trabalhei para responder **7 perguntas de negócio**, como:

1. Qual o perfil geográfico dos clientes da Zoop?
2. Qual a distribuição de faturamento por região?
3. Como estão os indicadores de vendas ao longo do tempo?
4. Entre outros insights estratégicos...

---

## 📈 Exemplos de Visualizações Criadas

- 📊 Gráficos de barras
- 📍 Mapas de calor
- 📈 Gráficos de linha
- 🌳 Treemaps

---

## 📂 Exemplo de Código Python Usado no Projeto

Aqui um exemplo de código que usei durante a análise de dados:

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Carregando os dados
df_vendas = pd.read_csv('vendas.csv')

# Exibindo as primeiras linhas
print(df_vendas.head())

E também um exemplo de criação de gráfico:
plt.figure(figsize=(10,6))
sns.barplot(x='regiao', y='faturamento', data=df_vendas, palette='Blues_d')
plt.title('Faturamento por Região - Zoop 2023')
plt.xlabel('Região')
plt.ylabel('Faturamento')
plt.show()
```

## 📚 Meu Aprendizado com esse Projeto
✨ Como estudante em formação, esse projeto me ajudou a:

Consolidar conhecimentos de manipulação de dados com Pandas

Praticar criação de gráficos

Aprender a trabalhar com bases reais

Integrar a IA como ferramenta de apoio no processo de análise de dados

## 🖥️ Como visualizar o projeto
👉 Você pode abrir o notebook diretamente no Google Colab clicando abaixo:
https://colab.research.google.com/drive/1ytq3ape_ncyJY8lH7YBf6ru_bxk3mpAp


## 🤝 Conecte-se comigo!
Se quiser acompanhar minha jornada como futuro Cientista de Dados:

LinkedIn

GitHub

##📌 Observação Importante:
Este projeto é um estudo, com fins exclusivamente educacionais, como parte da minha formação em Ciência de Dados.


---






