# 🏦 Sistema Inteligente de Análise de Churn Bancário - Grupo 5

Este projeto foi desenvolvido para o **Hackathon de Dados (Tema: Decisão Inteligente)**. O objetivo principal é prever o *Churn* (cancelamento de contrato) de clientes bancários, permitindo que a instituição tome decisões proativas para retenção.

---

## 🚀 O Problema e o Objetivo
Adquirir um novo cliente custa significativamente mais do que manter um atual. 
- **Problema:** Alta taxa de cancelamento de contratos.
- **Objetivo:** Utilizar Machine Learning (Classificação) para identificar perfis de risco e gerar insights estratégicos para o negócio.

---

## 🛠️ Arquitetura de Dados (Medallion)
Para este projeto, simulamos uma arquitetura profissional de engenharia de dados para garantir a qualidade da informação:

| Camada | Descrição | Processo |
| :--- | :--- | :--- |
| **Bronze** 🥉 | Dados Brutos | Carga original do dataset no banco `hackathon.db` via SQL para garantir a auditoria e persistência. |
| **Silver** 🥈 | Dados Limpos | Padronização de formatos, tratamento de nulos, remoção de duplicados e ajuste de consistência (ex: *Card Type*). |
| **Gold** 🥇 | Dados de Negócio | Agregações estratégicas e preparação final das variáveis para o modelo de Machine Learning. |

---

## 📈 Insights e Decisões Inteligentes
Com base na análise dos dados, o sistema recomenda:
1. **Venda Cruzada (Cross-sell):** Oferecer produtos específicos para clientes que possuem poucos produtos bancários ativos.
2. **Fidelização Regional:** Estratégias de marketing personalizadas para as regiões com maior índice de evasão.
3. **Benefícios por Renda:** Programas de cashback ou vantagens exclusivas alinhadas ao salário estimado do cliente.

---

## 🔧 Tecnologias Utilizadas
- **Linguagem:** Python 3
- **Bibliotecas de Dados:** Pandas, Numpy
- **Banco de Dados:** SQLite (SQL)
- **Visualização:** Matplotlib / Seaborn
- **Plataforma:** Google Colab / Databricks

---

## 📂 Como Rodar o Projeto
1. Clone este repositório.
2. Certifique-se de ter o arquivo `Bank_Customer_Churn.csv` no mesmo diretório (ou use o link direto configurado no notebook).
3. Execute o notebook `Hackathon_Dados.ipynb` em um ambiente Jupyter ou Google Colab.

---

## 👥 Integrantes - Grupo 5
- **Bárbara [Seu Sobrenome]** - Data Engineer/Manager
- [Nome do Colega 2]
- [Nome do Colega 3]

---
> *Este projeto faz parte do portfólio de estudos em Engenharia de Dados.*
