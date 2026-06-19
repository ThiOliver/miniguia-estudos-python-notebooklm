# Miniguia de Estudos com NotebookLM — Python para Análise de Dados

> Projeto prático do desafio **Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM** — DIO

---

## Contexto e Objetivos

Este projeto utiliza o **NotebookLM** como ferramenta de aprendizagem ativa para explorar o ecossistema **Python voltado à Análise de Dados**. O objetivo é dominar os principais conceitos de Python, NumPy, Pandas, Seaborn e Matplotlib, utilizando IA para organizar o conhecimento, gerar resumos e criar um guia de estudos reutilizável.

Objetivos específicos:
- Compreender a sintaxe e os recursos fundamentais do Python 3
- Entender como manipular dados com NumPy e Pandas
- Aprender a criar visualizações com Matplotlib e Seaborn
- Usar o NotebookLM para consolidar o aprendizado com resumos e glossário

---

## Curadoria de Fontes

Fontes abertas selecionadas e adicionadas ao NotebookLM:

| # | Fonte | Descrição |
|---|-------|-----------|
| 1 | [Tutorial Oficial Python PT-BR](https://docs.python.org/pt-br/3/tutorial/) | Tutorial completo do Python 3 em português |
| 2 | [NumPy Documentation](https://numpy.org/doc/stable/) | Documentação oficial do NumPy |
| 3 | [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html) | Guia do usuário do Pandas |
| 4 | [Seaborn Documentation](https://seaborn.pydata.org/index.html) | Documentação oficial do Seaborn |
| 5 | [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/coding_shortcuts.html) | Tutoriais e boas práticas do Matplotlib |
| 6 | [Python 3.14 Docs PT-BR](https://docs.python.org/pt-br/3.14/) | Documentação da versão mais recente do Python em português |

---

## Engenharia de Prompts e Cicatrizes

Abaixo estão os prompts reais utilizados no NotebookLM, com as respostas obtidas diretamente da ferramenta.

---

### Prompt 1 — Conceitos fundamentais de Python

**Pergunta:** *Quais são os conceitos fundamentais de Python que um iniciante deve dominar?*

**Resposta obtida:**

**1. Sintaxe e Fluxo de Controle**
A sintaxe elegante e a tipagem dinâmica facilitam o aprendizado. Estruturas essenciais: `if`, `for` e `while`. Ferramentas: `range()`, `break`, `continue` e `match` para correspondência de padrões.

**2. Estruturas de Dados Embutidas**
- Listas e Tuplas: sequências mutáveis e imutáveis
- Conjuntos (Sets): coleções sem duplicatas
- Dicionários: mapeamentos de chave-valor

**3. Funções e Modularização**
- Funções com `def`, argumentos nomeados, valores padrão e `lambda`
- Importação de módulos da Biblioteca Padrão e de terceiros (NumPy, Pandas)

**4. Programação Orientada a Objetos (POO)**
- Classes, instâncias, métodos e herança

**5. Tratamento de Erros e E/S**
- `try` e `except` para lidar com erros de forma graciosa
- Leitura e gravação de arquivos

**6. Conceitos para Análise de Dados**
- Arrays Multidimensionais (NumPy), Series e DataFrames (Pandas)
- Matplotlib/Seaborn: interface Axes vs. interface pyplot

---

### Prompt 2 — Glossário com os 10 termos mais importantes

**Pergunta:** *Crie um glossário com os 10 termos mais importantes*

**Resposta obtida:**

| # | Termo | Definição |
|---|-------|-----------|
| 1 | **Interpretador** | Motor que processa o código Python, permitindo execução em diversas plataformas |
| 2 | **Array (NumPy)** | Objeto de matriz multidimensional; unidade fundamental para computação científica |
| 3 | **DataFrame (Pandas)** | Estrutura bidimensional rotulada para manipulação e análise de dados estruturados |
| 4 | **Series (Pandas)** | Estrutura unidimensional rotulada; componente básico das colunas de um DataFrame |
| 5 | **Axes (Matplotlib)** | Interface primária para criação de gráficos, onde elementos como linhas e etiquetas são desenhados |
| 6 | **Figura (Figure)** | Objeto de nível superior que atua como contêiner de todos os elementos do gráfico |
| 7 | **Seaborn** | Biblioteca baseada no Matplotlib com interface de alto nível para gráficos estatísticos |
| 8 | **Indexação** | Processo de selecionar subconjuntos de dados por rótulo ou posição |
| 9 | **Group by** | Lógica split-apply-combine para agrupar dados, aplicar funções e combinar resultados |
| 10 | **Dados Ausentes (Missing Data)** | Representação e tratamento de valores nulos (NA); passo crítico na limpeza de dados |

---

### Prompt 3 — Resumo estruturado do conteúdo das fontes

**Pergunta:** *Faça um resumo estruturado do conteúdo das fontes*

**Resposta obtida:**

**1. Python (v3.14):** Linguagem poderosa, fácil de aprender, ideal para scripts. Inclui estruturas de dados de alto nível, controle de fluxo (`if`, `for`, `match`) e suporte a POO. Extensível com C/C++.

**2. NumPy (v2.4):** Pacote fundamental para computação científica. Array multidimensional de alta performance com rotinas para matemática, lógica, álgebra linear, estatística e simulação.

**3. Pandas (v3.0.3):** Biblioteca central para dados estruturados. Series e DataFrame. Funcionalidades: E/S em CSV/JSON/SQL/Excel/Parquet, indexação, merge, group by, dados ausentes e séries temporais.

**4. Matplotlib (v3.11.0) e Seaborn (v0.13.2):**
- Matplotlib: atalhos para API Axes, método `set()`, diferença entre interface Axes e pyplot
- Seaborn: interface de alto nível para gráficos relacionais, de distribuição, catégoricos e de regressão

**5. Documentação:** Tutoriais como '10 minutes to pandas' e 'Absolute Beginner's Guide to NumPy', manuais de API e glossários oficiais.

---

### Prompt 4 — Aplicações práticas do assunto

**Pergunta:** *Quais são as aplicações práticas deste assunto?*

**Resposta obtida:**

**1. Computação Científica (NumPy):** Álgebra linear, transformadas de Fourier, simulações e processamento de grandes volumes numéricos.

**2. Engenharia de Dados (Pandas):** Limpeza de dados, integração de bases (merge/join), E/S em CSV/Excel/SQL/Parquet, tabelas dinâmicas e relatórios.

**3. Séries Temporais (Pandas):** Conversão de timestamps, geração de intervalos de datas, fusos horários e reamostragem (resampling).

**4. Visualização (Matplotlib + Seaborn):** Plots estatísticos (regressão, distribuição, catégoricos), controle refinado sobre gráficos e exportação em PNG.

**5. Automação e Desenvolvimento (Python):** Scripting, prototipagem rápida, extensibilidade com C/C++ e escalabilidade via chunking.

---

### Prompt 5 — Prompts reutilizáveis para revisão

**Pergunta:** *Crie um conjunto de prompts que eu possa reutilizar para revisar este tema*

**Resposta obtida:**

**Categoria 1 — Fundamentos de Python**
- *Explique a diferença técnica entre listas, tuplas, sets e dicionários em Python, abordando mutabilidade e performance.*
- *Crie um exemplo com a instrução match (Python 3.10+) para processar diferentes tipos de respostas de uma API.*
- *Como funcionam as expressões lambda e quando são preferíveis ao def em fluxos de análise de dados?*

**Categoria 2 — NumPy**
- *O que torna o ndarray do NumPy mais eficiente que listas nativas para operações matemáticas em larga escala?*
- *Demonstre álgebra linear (multiplicação de matrizes e inversão) e geração de números aleatórios com NumPy.*

**Categoria 3 — Pandas**
- *Diferencie Series e DataFrame, explicando como rótulos de índice facilitam o alinhamento de dados.*
- *Como funciona a lógica split-apply-combine no groupby? Calcule média e soma simultaneamente por categoria.*
- *Quais estratégias para dados ausentes (NaN) e como decidir entre fillna ou dropna?*
- *Quais as vantagens de usar Parquet em vez de CSV para grandes conjuntos de dados?*

**Categoria 4 — Visualização**
- *Explique a diferença entre a interface pyplot e a interface Axes no Matplotlib. Quando usar o método set()?*
- *Compare relplot, displot e catplot no Seaborn: quando usar cada um em análise exploratória?*
- *Como usar temas e paletas de cores no Seaborn para melhorar a legibilidade estatística?*

**Categoria 5 — Desafios Práticos**
- *Descreva o fluxo completo para analisar um CSV de vendas: importação, limpeza, agrupamento por região e gráfico com Seaborn.*
- *Como o Pandas facilita séries temporais? Explique resampling e conversão de strings em datas.*

> **Dica de Estudo:** Tente responder sem consultar a documentação primeiro, depois valide com as fontes para checar indexação, vetorização e estruturas de dados corretas.

---

## Tecnologias e Ferramentas

- [NotebookLM](https://notebooklm.google.com) — IA para organização e estudo
- [Python 3](https://www.python.org/) — Linguagem principal
- [NumPy](https://numpy.org/) — Computação numérica
- [Pandas](https://pandas.pydata.org/) — Análise de dados
- [Matplotlib](https://matplotlib.org/) — Visualização de dados
- [Seaborn](https://seaborn.pydata.org/) — Visualização estatística

---

*Projeto desenvolvido como parte do desafio **Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM** na plataforma [DIO](https://web.dio.me).*
