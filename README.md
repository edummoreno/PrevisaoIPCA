
# 📈 Previsão do IPCA utilizando Regressão Linear em Python

Este projeto consiste na previsão do Índice Nacional de Preços ao Consumidor Amplo (IPCA), o principal índice brasileiro que mede a inflação oficial, através de modelos de regressão supervisionada utilizando Python.

## 🎯 Objetivo

Construir e avaliar um modelo de regressão linear capaz de prever o valor mensal do IPCA utilizando dados históricos disponibilizados pelo IBGE.

## 📚 Fonte dos Dados

Os dados históricos do IPCA foram extraídos diretamente do portal SIDRA do IBGE:
- [Portal SIDRA - IBGE](https://sidra.ibge.gov.br)

## 🛠️ Ferramentas e Bibliotecas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## 🔧 Metodologia

1. **Coleta e carregamento dos dados históricos**.
2. **Análise Exploratória (EDA)** dos dados com visualizações gráficas.
3. **Engenharia de atributos** para criação de variáveis preditoras (mês, ano, IPCA do mês anterior).
4. **Divisão do dataset** em treino e teste (80% treino, 20% teste).
5. **Aplicação do modelo de regressão linear** para prever o IPCA.
6. **Avaliação de desempenho** com métricas como RMSE e R².

## 📊 Resultados

| Métrica | Resultado |
|---------|-----------|
| RMSE    | xx.xx     |
| R²      | xx.xx%    |

*(Os valores finais serão atualizados após execução dos modelos.)*

## 📌 Próximos Passos

- Aplicar modelos avançados como Random Forest e XGBoost para comparação.
- Incluir variáveis macroeconômicas adicionais (Selic, PIB, taxa de desemprego).
- Construção de aplicação Web com Streamlit para visualização interativa.

## 📄 Estrutura do Repositório

```
📁 ipca_regression_project
├── 📁 data
│   └── ipca.csv
├── 📁 src
│   └── ipca_regressao.py
├── 📁 images
│   └── resultado_grafico.png
└── README.md
```

## 📞 Contato

[Seu Nome](https://linkedin.com/in/seu-linkedin)
