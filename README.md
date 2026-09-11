# Análise Exploratória de Dados (EDA): Avaliação de Risco de Crédito

Projeto desenvolvido para a disciplina de **Técnicas de Programação I (Python)** do Programa de Formação Continuada **CaixaVerso**.

---

##  Objetivo do Projeto
O objetivo deste estudo é analisar padrões comportamentais e sociodemográficos associados à inadimplência em cartões de crédito, utilizando técnicas de limpeza de dados, engenharia de atributos e análise exploratória visual.

---

##  Perguntas de Negócio
O projeto foi estruturado para responder a duas hipóteses centrais de crédito:

1. **Renda vs. Inadimplência:** Clientes com maior renda anual apresentam menores taxas de inadimplência?
2. **Estabilidade Pessoal vs. Risco:** O tipo de moradia ou o estado civil têm relação direta com o risco de atraso de pagamento?

---

## Sobre a Base de Dados
A base de dados utilizada é composta por dados **completamente anonimizados** de proponentes de cartões de crédito e seus históricos mensais de faturas. Qualquer dado de identificação pessoal (como nome, CPF ou localização exata) foi desidentificado para garantir conformidade e privacidade.

O conjunto é composto por duas tabelas principais cruzadas pelo identificador do cliente:
- **Tabela Cadastral:** Informações demográficas e socioeconômicas (renda anual, idade, tempo de emprego, posse de bens, estado civil e tipo de moradia).
- **Histórico de Pagamento:** Comportamento mensal da fatura com defasagem temporal e status de atraso/liquidação (classificados entre faixas de inadimplência de 30 a mais de 150 dias, faturas quitadas ou sem saldo devedor).

🔗 **Fonte e Documentação do Dataset (Kaggle):**  
[Credit Card Approval Prediction Dataset](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction)

---

## Tecnologias Utilizadas
- **Linguagem:** Python 3
- **Manipulação de Dados:** Pandas, NumPy
- **Visualização:** Matplotlib, Seaborn
- **Versionamento:** Git e GitHub

---

## Integrantes
- Eduardo Roquette
- Fernando Araújo
- Giselle