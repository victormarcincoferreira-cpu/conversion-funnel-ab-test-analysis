# 🧪 A/B Test Analysis — Conversion Funnel

## 📌 Sobre o projeto
Este projeto consiste na análise estatística de um experimento A/A/B conduzido por uma plataforma de e-commerce, com o objetivo de avaliar o impacto de um novo sistema de recomendação no comportamento dos usuários.

## 🎯 Objetivo
Avaliar se o novo sistema melhora as taxas de conversão ao longo do funil:

login → product_page → product_cart → purchase

A hipótese de negócio previa um aumento mínimo de 10% nas conversões.

---

## 🧪 Metodologia

- Análise exploratória de dados (EDA)
- Limpeza e validação dos dados
- Construção de funil de conversão
- Teste estatístico (teste Z para proporções)
- Nível de significância: 5%

---

## ⚠️ Validação do experimento

Foram identificados fatores que impactam a confiabilidade:

- Desbalanceamento entre grupos
- Usuários em múltiplos testes
- Redução de eventos ao final do experimento

---

## 📊 Principais resultados

- O novo sistema reduziu a conversão na etapa de `product_page`
- Não houve diferença estatisticamente significativa nas demais etapas
- O funil apresentou comportamento esperado

---

## 📈 Conclusão

O novo sistema de recomendação **não apresentou melhoria de performance** e teve impacto negativo na etapa inicial do funil.

📌 Recomendação: **não implementar a solução neste momento**

---

## 🚫 Sobre os dados

Os dados utilizados neste projeto são provenientes de um ambiente educacional e **não podem ser disponibilizados publicamente**.

Este repositório tem como objetivo demonstrar:
- Estrutura de análise
- Raciocínio estatístico
- Aplicação de testes de hipótese

---

## 🛠️ Tecnologias utilizadas

- Python (Pandas, NumPy)
- Statsmodels
- Matplotlib / Seaborn

---
📌 Autor

Victor Marcinco

# 🧰 5. requirements.txt

```txt
pandas
numpy
matplotlib
seaborn
statsmodels
```

## ▶️ Como executar

```bash
pip install -r requirements.txt
```
# NOTE:
# Os dados não estão disponíveis por restrições de compartilhamento.
# Este notebook demonstra o processo analítico e a aplicação dos métodos estatísticos.
