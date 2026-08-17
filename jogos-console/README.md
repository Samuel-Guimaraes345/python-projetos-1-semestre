# 🎮 Jogos de Console — Python

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![ipywidgets](https://img.shields.io/badge/ipywidgets-Colab-orange?style=for-the-badge)

## 📖 Sobre

Coleção de 3 jogos desenvolvidos em Python, explorando lógica de jogos, aleatoriedade, e no caso da Forca, uma interface visual interativa dentro do Google Colab.

## 🎲 Projetos

### 1. Jogo do Nim (`jogo_do_nim.py`)
Jogo de estratégia matemática onde dois jogadores retiram peças de um monte, e quem tira a última peça vence. O computador possui 3 níveis de dificuldade — no nível difícil, ele usa **aritmética modular** para calcular a jogada ótima e forçar o jogador a uma posição de derrota.

📄 O raciocínio matemático completo por trás da estratégia está documentado em [`relatorio_jogo_do_nim.docx`](./relatorio_jogo_do_nim.docx).

### 2. Jogo da Forca (`jogo_da_forca.py`)
Duas versões no mesmo arquivo: uma via terminal (texto) e outra com **interface gráfica interativa** usando `ipywidgets`, incluindo desenho ASCII progressivo do boneco da forca, contador de tentativas e botão de reiniciar.

### 3. Jogo do Bixo (`jogo_do_bixo.py`)
Simulador de apostas com 3 modalidades (Milhar, Trinca, Grupo), sorteio randômico com semente configurável e sistema de cálculo de prêmios baseado nas regras de cada modalidade.

## 🛠️ Tecnologias

- **Python 3** — Lógica principal
- **random** — Geração de números aleatórios e sorteios
- **ipywidgets** — Interface interativa (Jogo da Forca)

## 🚀 Como Executar

As instruções completas (Google Colab) estão no [README principal do repositório](../README.md).

## 🧠 Aprendizados

- Lógica de jogos por turnos e condições de vitória/derrota
- Uso de **aritmética modular** aplicada a estratégias de jogo (Nim)
- Manipulação de **strings e sets** para rastrear letras acertadas/erradas (Forca)
- Criação de **interfaces interativas** com widgets no Colab
- Tratamento de exceções e validação de entrada do usuário
