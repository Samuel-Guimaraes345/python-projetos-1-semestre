# 📈 Dashboard Financeiro com Dados Reais

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-Yahoo%20Finance-purple?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)

## 📖 Sobre

Dois algoritmos de análise financeira usando **dados reais da B3** (Bolsa de Valores brasileira), obtidos via Yahoo Finance. O projeto evolui de uma simulação simples de carteira até uma análise técnica de nível profissional.

## 📊 Projetos

### 1. Simulação de Investimento com Risco (`simulacao_investimento_risco.py`)
Duas simulações: uma com **ruído aleatório controlado** (movimento browniano simplificado) e outra com dados reais de 4 bancos brasileiros (Itaú, Bradesco, Banco do Brasil, Santander), comparando o desempenho de uma carteira balanceada contra os ativos individuais.

### 2. Correlação entre Ativos (`correlacao_acoes.py`)
Analisa a correlação entre duas ações (PETR4 e VALE3) através de um gráfico de dispersão, usando dados reais baixados via `yfinance`.

### 3. Análise Técnica Completa
📄 Documentado em detalhe no relatório [`relatorio_analise_financeira.docx`](./relatorio_analise_financeira.docx), que cobre dois algoritmos:
- **Relatório com gráficos em Excel**: simula aportes mensais de R$500 na PETR4, com gráficos embutidos na planilha via `openpyxl.chart`
- **Análise técnica avançada**: calcula indicadores usados por analistas reais — **Médias Móveis (MM20/MM50)**, **RSI** (Índice de Força Relativa), **MACD**, além de métricas de risco como **Volatilidade Anualizada**, **Sharpe Ratio** e **Max Drawdown**, comparando uma estratégia de cruzamento de médias contra Buy and Hold

## 🛠️ Tecnologias

- **Python 3**
- **pandas** — Manipulação de séries temporais financeiras
- **numpy** — Cálculos estatísticos (volatilidade, Sharpe Ratio)
- **yfinance** — Coleta de dados reais da bolsa de valores
- **matplotlib / plotly** — Visualização de gráficos
- **openpyxl** — Exportação de relatórios com gráficos para Excel

## 🚀 Como Executar

```bash
pip install pandas numpy yfinance matplotlib openpyxl plotly
python simulacao_investimento_risco.py
python correlacao_acoes.py
```

## 🧠 Aprendizados

- Coleta e tratamento de **dados financeiros reais** (incluindo correção de `MultiIndex` do yfinance)
- Cálculo de **indicadores técnicos** usados profissionalmente no mercado (RSI, MACD, médias móveis)
- Cálculo de **métricas de risco** (volatilidade, Sharpe Ratio, drawdown)
- Geração de **gráficos embutidos em Excel** via `openpyxl.chart`
- Simulação de estratégias de investimento e comparação de performance
