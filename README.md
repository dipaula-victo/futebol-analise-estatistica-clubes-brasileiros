# 📊 Análise Estatística de Clubes Brasileiros de Futebol

Este projeto tem como objetivo analisar, a partir de dados reais, quais estatísticas individuais e coletivas são mais relevantes para o sucesso competitivo de cinco clubes do futebol brasileiro: **Flamengo, Palmeiras, São Paulo, Corinthians e Ituano**.  

A pesquisa combina **análise exploratória de dados**, **testes estatísticos** e **modelagem preditiva**, visando oferecer uma base sólida para tomadas de decisão estratégicas no esporte.

---

## 🎯 Objetivo

Investigar o impacto de estatísticas por meio de:
- Desempenho geral dos times
- Visualização gráfica de resultados
- Correlações
- Análise probabilística

Além disso, o projeto busca comparar o desempenho de clubes com diferentes níveis de investimento e estrutura, explorando como recursos influenciam a performance em campo.

---

## 🧠 Metodologia

- 📥 Coleta e limpeza de dados (dataset público)
- 📊 Análise exploratória com `pandas` e `matplotlib`
- 📈 Testes de correlação e significância
- 🤖 Modelagem preditiva para prever resultados com base nas estatísticas
- 🏁 Interpretação dos resultados e insights gerenciais

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Google Colab
- Pandas
- Matplotlib / Seaborn
- Numpy
- Tubulate

---

## ⚽ Times Analisados

- Flamengo  
- Palmeiras  
- São Paulo  
- Corinthians  
- Ituano  

> A escolha dos clubes visa comparar equipes de grande porte com um time de menor expressão para analisar o papel dos recursos no desempenho.

---

## 📈 Resultados Esperados

- Identificação das métricas mais determinantes para vitórias
- Comparações entre times de diferentes portes

---

## 📌 Conclusões

As análises descritivas e os boxplots confirmaram que os clubes brasileiros estudados — **Flamengo, Palmeiras, São Paulo, Corinthians e Ituano** — possuem **diferenças claras em estilo de jogo e desempenho ofensivo**, evidenciadas por métricas como:

- Precisão de passes  
- Criação e conversão de chances  
- Posse de bola  
- Rating individual dos jogadores  

### 🔍 Destaques por clube:

- **Flamengo e Palmeiras**: mais ofensivos e dominantes na posse de bola; apresentam maior criação de jogadas, conversão de chances e atletas com ratings excepcionais.
- **São Paulo**: prioriza a posse, mas com menor eficácia ofensiva.
- **Corinthians**: perfil mais equilibrado, mas com desempenho ofensivo inferior aos líderes.
- **Ituano**: estilo mais reativo, com menor posse e volume ofensivo, refletindo limitações de elenco e estratégia.

### 📈 Insights estatísticos:

- **Eficiência ofensiva** (gols e finalizações no alvo) foi o fator com maior impacto no rating dos jogadores — mais relevante do que precisão de passe.
- **Flamengo e Palmeiras** apresentaram as maiores médias de gols esperados por tentativa, indicando maior poder de finalização.
- **São Paulo e Corinthians** foram consistentes, com leve oscilação.
- **Ituano** teve a menor média, destacando a necessidade de melhorar ofensivamente.

🔗 Essa análise reforça como a **estatística esportiva pode ser uma poderosa aliada tática**, ajudando técnicos e clubes a tomarem decisões baseadas em dados reais.

---

## 📂 Organização do Projeto


```bash
📁 futebol-analise-estatistica-clubes-brasileiros
│
├── futebol_analise.ipynb        # Notebook principal
├── datasets/                    # Arquivos CSV utilizados
├── imagens/                     # Visualizações geradas
└── README.md
