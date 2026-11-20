# Detecção de Fraude em Cartão de Crédito

Projeto desenvolvido no Google Colab com o conjunto de dados `creditcard.csv` (284.807 transações, altamente desbalanceado).

## Modelo e Resultados
- Modelo principal: Random Forest com `class_weight="balanced"`
- Limiar (*threshold*) ajustado para `0.30`
- *Recall* na classe de fraude: `0.8469`
- *F1-score* na classe de fraude: `0.8830`

## Variáveis Mais Relevantes
`V14`, `V10`, `V12`, `V4` e `V17`.
