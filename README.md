# 🧠 Score de Crédito com IA

Este projeto tem como objetivo prever a probabilidade de um cliente pagar ou não um empréstimo com base em características fornecidas no cadastro, utilizando técnicas de Machine Learning.

> 🚀 Projeto desenvolvido durante a **Imersão Python** promovida pela **Hashtag Treinamentos**.

---

## 📊 Objetivo do Projeto

O propósito principal é auxiliar instituições financeiras a tomarem decisões mais seguras sobre concessão de crédito. Com isso, é possível reduzir a inadimplência utilizando um modelo inteligente de previsão.


## 🧾 Dados Utilizados

Foram utilizadas duas bases de dados fornecidas durante a Imersão:

1. **Base de Treinamento** – usada para treinar o modelo de IA.
2. **Base de Teste** – usada para testar a eficácia do modelo em prever novos casos.

Os dados incluem informações como:
- ID do cliente
- Gênero
- Idade
- Estado civil
- Profissão
- Renda anual
- Pontuação de crédito
- Quantidade de filhos
- Score interno da empresa
- Pagou ou não o empréstimo

---

## 🛠️ Tecnologias e Bibliotecas

- Python 🐍
- Pandas
- Scikit-learn
- Plotly Express
- Numpy
- Jupyter Notebook
- Openpyxl
- NBFormat
- Matplotlib

---

## 🔍 Etapas do Projeto

1. **Leitura e Análise Exploratória dos Dados**
2. **Limpeza e Tratamento dos Dados**
3. **Divisão em Treino e Teste**
4. **Treinamento de Modelos (Árvore de Decisão, Random Forest)**
5. **Avaliação de Acurácia**
6. **Aplicação do Modelo sobre novos dados**
7. **Geração de gráficos para análise dos resultados**

---

## 📈 Resultados Obtidos

- Foi possível treinar um modelo com alta taxa de acerto na predição de inadimplência.
- A análise dos dados possibilitou identificar padrões e características comuns entre os bons e maus pagadores.
- O modelo pode ser facilmente adaptado para uso real em empresas do setor financeiro.

---

## 🧠 Principais Insights

- Clientes com score interno baixo têm mais chance de inadimplência.
- Renda anual e idade também estão correlacionadas com a probabilidade de não pagamento.
- O modelo Random Forest teve melhor desempenho entre os testados.

---

## 📁 Estrutura do Projeto
```bash
📦 python-score-credito-ia
├── 📊 dados
│ ├── clientes_treino.xlsx
│ └── clientes_novos.xlsx
├── 📓 inicial.ipynb 
└── README.md
```

## 💡 Como Executar

1. **Clone o repositório:**
```bash
git clone https://github.com/liveavasconcelos/python-score-credito-ia.git
```

2. **Instale as dependências:**
```bash
pip install pandas sklearn
```

3. **Certifique-se de que a  extensão do Jupyter já está instalada e execute inicial.ipynb.**

## 📚 Sobre o Projeto
Este projeto foi desenvolvido com base no conteúdo da Imersão Python da Hashtag Treinamentos, como parte de uma jornada prática para aprender análise de dados e inteligência artificial com Python.

## 👩🏻‍💻 Autora
Livea Mendes de Vasconcelos

[GitHub](https://https://github.com/liveavasconcelos) | [LinkedIn](https://www.linkedin.com/in/livea-vasconcelos/)

