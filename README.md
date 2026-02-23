# 📊 Análise de Evasão de Clientes (Churn)

## 📌 Descrição do Projeto

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (Churn) em uma empresa de telecomunicações, utilizando Python e suas principais bibliotecas para realizar o processo de ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados (EDA).

A análise busca identificar padrões de comportamento associados ao cancelamento de serviços, permitindo que a equipe de Data Science utilize esses insights no desenvolvimento de modelos preditivos e estratégias de retenção de clientes.

---

## 🎯 Objetivos

- Importar e manipular dados de uma API
- Aplicar conceitos de ETL
- Realizar limpeza e tratamento de dados
- Conduzir análise exploratória de dados (EDA)
- Identificar fatores associados à evasão de clientes
- Gerar insights estratégicos para redução de churn

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

---

## 🔄 ETL

### Extração
Os dados foram coletados a partir de uma API no formato JSON aninhado.

### Transformação
Foram realizados os seguintes tratamentos:

- Normalização dos dados utilizando `json_normalize()`
- Conversão de variáveis binárias ("Yes"/"No") para valores numéricos
- Tratamento de valores nulos
- Conversão de variáveis numéricas armazenadas como texto
- Criação de faixas de tempo de permanência dos clientes (tenure)

### Carga
Os dados tratados foram utilizados para análise exploratória.

---

## 📊 Análise Exploratória de Dados

Foram realizadas análises considerando:

- Taxa geral de churn
- Churn por tipo de contrato
- Churn por tipo de serviço de internet
- Churn por método de pagamento
- Churn por tempo de permanência do cliente (tenure)
- Correlação entre variáveis

---

## 🧠 Principais Insights

- Clientes com contrato mensal apresentam maior taxa de evasão;
- O serviço de fibra óptica está associado a maiores taxas de churn;
- O método de pagamento "Electronic Check" apresentou maior evasão;
- Clientes com menor tempo de permanência possuem maior probabilidade de cancelar;
- O tempo de permanência (tenure) possui correlação negativa com o churn.

---

## 💡 Recomendações

- Incentivar contratos de maior duração;
- Focar em estratégias de retenção no primeiro ano de contrato;
- Avaliar a experiência de clientes com serviço de fibra óptica;
- Promover métodos de pagamento automáticos;
- Desenvolver campanhas de engajamento para novos clientes.

---

## 📂 Estrutura do Projeto
