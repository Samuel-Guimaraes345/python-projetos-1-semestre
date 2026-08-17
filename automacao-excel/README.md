# 📊 Automação de Excel com Python

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![openpyxl](https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

## 📖 Sobre

Dois projetos de automação de planilhas Excel usando a biblioteca `openpyxl`, aplicando conceitos de manipulação de arquivos e cálculo automatizado.

## 📊 Projetos

### 1. CRUD de Alunos (`crud_alunos_excel.py`)
Sistema de linha de comando completo para gerenciar uma planilha de alunos: Criar, Listar, Editar e Apagar registros diretamente em um arquivo `.xlsx`, com validação de entrada e menu interativo.

### 2. Calculadora Financeira Automatizada (`calculadora_financeira_excel.py`)
Script que cria uma planilha do zero, preenche com dados de clientes fictícios e calcula automaticamente o Valor Futuro de cada investimento usando a fórmula de juros compostos, salvando o resultado direto na planilha.

## 🛠️ Tecnologias

- **Python 3**
- **openpyxl** — Leitura, escrita e edição de arquivos `.xlsx`

## 🚀 Como Executar

```bash
pip install openpyxl
python crud_alunos_excel.py
python calculadora_financeira_excel.py
```

## 🧠 Aprendizados

- Leitura e escrita de arquivos Excel programaticamente
- Criação de menus interativos em loop (`while True`)
- Validação robusta de entrada do usuário com `try/except`
- Aplicação de fórmulas financeiras (juros compostos) de forma automatizada
