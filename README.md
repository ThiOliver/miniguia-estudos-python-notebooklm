# Miniguia de Estudos com NotebookLM — Python para Analise de Dados

> Projeto pratico do desafio **Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM** — DIO

---

## Contexto e Objetivos

Este projeto utiliza o **NotebookLM** como ferramenta de aprendizagem ativa para explorar o ecossistema **Python voltado a Analise de Dados**. O objetivo e dominar os principais conceitos de Python, NumPy, Pandas, Seaborn e Matplotlib, utilizando IA para organizar o conhecimento, gerar resumos e criar um guia de estudos reutilizavel.

Objetivos especificos:
- Compreender a sintaxe e os recursos fundamentais do Python 3
- Entender como manipular dados com NumPy e Pandas
- Aprender a criar visualizacoes com Matplotlib e Seaborn
- Usar o NotebookLM para consolidar o aprendizado com resumos e glossario

---

## Curadoria de Fontes

Fontes abertas selecionadas e adicionadas ao NotebookLM:

| # | Fonte | Descricao |
|---|-------|-----------|
| 1 | [Tutorial Oficial Python PT-BR](https://docs.python.org/pt-br/3/tutorial/) | Tutorial completo do Python 3 em portugues |
| 2 | [NumPy Documentation](https://numpy.org/doc/stable/) | Documentacao oficial do NumPy |
| 3 | [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html) | Guia do usuario do Pandas |
| 4 | [Seaborn Documentation](https://seaborn.pydata.org/index.html) | Documentacao oficial do Seaborn |
| 5 | [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/coding_shortcuts.html) | Tutoriais e boas praticas do Matplotlib |
| 6 | [Python 3.14 Docs PT-BR](https://docs.python.org/pt-br/3.14/) | Documentacao da versao mais recente do Python em portugues |

---

## Engenharia de Prompts e Cicatrizes

Abaixo estao os prompts reais utilizados no NotebookLM, com as respostas obtidas diretamente da ferramenta.

---

### Prompt 1 — Conceitos fundamentais de Python

**Pergunta:** *Quais sao os conceitos fundamentais de Python que um iniciante deve dominar?*

**Resposta obtida:**

**1. Sintaxe e Fluxo de Controle**
A sintaxe elegante e a tipagem dinamica facilitam o aprendizado. Estruturas essenciais: `if`, `for` e `while`. Ferramentas: `range()`, `break`, `continue` e `match` para correspondencia de padroes.

**2. Estruturas de Dados Embutidas**
- Listas e Tuplas: sequencias mutaveis e imutaveis
- Conjuntos (Sets): colecoes sem duplicatas
- Dicionarios: mapeamentos de chave-valor

**3. Funcoes e Modularizacao**
- Funcoes com `def`, argumentos nomeados, valores padrao e `lambda`
- Importacao de modulos da Biblioteca Padrao e de terceiros (NumPy, Pandas)

**4. Programacao Orientada a Objetos (POO)**
- Classes, instancias, metodos e heranca

**5. Tratamento de Erros e I/O**
- `try` e `except` para erros graciosamente
- Leitura e gravacao de arquivos

**6. Conceitos para Analise de Dados**
- Arrays Multidimensionais (NumPy), Series e DataFrames (Pandas)
- Matplotlib/Seaborn: interface Axes vs. interface pyplot

---

### Prompt 2 — Glossario com os 10 termos mais importantes

**Pergunta:** *Crie um glossario com os 10 termos mais importantes*

**Resposta obtida:**

| # | Termo | Definicao |
|---|-------|-----------|
| 1 | **Interpretador** | Motor que processa o codigo Python, permitindo execucao em diversas plataformas |
| 2 | **Array (NumPy)** | Objeto de matriz multidimensional; unidade fundamental para computacao cientifica |
| 3 | **DataFrame (Pandas)** | Estrutura bidimensional rotulada para manipulacao e analise de dados estruturados |
| 4 | **Series (Pandas)** | Estrutura unidimensional rotulada; componente basico das colunas de um DataFrame |
| 5 | **Axes (Matplotlib)** | Interface primaria para criacao de graficos, onde elementos como linhas e etiquetas sao desenhados |
| 6 | **Figura (Figure)** | Objeto de nivel superior que atua como container de todos os elementos do grafico |
| 7 | **Seaborn** | Biblioteca baseada no Matplotlib com interface de alto nivel para graficos estatisticos |
| 8 | **Indexacao** | Processo de selecionar subconjuntos de dados por rotulo ou posicao |
| 9 | **Group by** | Logica split-apply-combine para agrupar dados, aplicar funcoes e combinar resultados |
| 10 | **Dados Ausentes (Missing Data)** | Representacao e tratamento de valores nulos (NA); passo critico na limpeza de dados |

---

### Prompt 3 — Resumo estruturado do conteudo das fontes

**Pergunta:** *Faca um resumo estruturado do conteudo das fontes*

**Resposta obtida:**

**1. Python (v3.14):** Linguagem poderosa, facil de aprender, ideal para scripts. Inclui estruturas de dados de alto nivel, controle de fluxo (`if`, `for`, `match`) e suporte a POO. Extensivel com C/C++.

**2. NumPy (v2.4):** Pacote fundamental para computacao cientifica. Array multidimensional de alta performance com rotinas para matematica, logica, algebra linear, estatistica e simulacao.

**3. Pandas (v3.0.3):** Biblioteca central para dados estruturados. Series e DataFrame. Funcionalidades: I/O em CSV/JSON/SQL/Excel/Parquet, indexacao, merge, group by, ausentes e series temporais.

**4. Matplotlib (v3.11.0) e Seaborn (v0.13.2):**
- Matplotlib: atalhos para API Axes, metodo `set()`, diferenca entre interface Axes e pyplot
- Seaborn: interface de alto nivel para graficos relacionais, distribuicao, categoricos e regressao

**5. Documentacao:** Tutoriais como '10 minutes to pandas' e 'Absolute Beginner's Guide to NumPy', manuais de API e glossarios oficiais.

---

### Prompt 4 — Aplicacoes praticas do assunto

**Pergunta:** *Quais sao as aplicacoes praticas deste assunto?*

**Resposta obtida:**

**1. Computacao Cientifica (NumPy):** Algebra linear, transformadas de Fourier, simulacoes e processamento de grandes volumes numericos.

**2. Engenharia de Dados (Pandas):** Limpeza de dados, integracao de bases (merge/join), I/O em CSV/Excel/SQL/Parquet, tabelas dinamicas e relatorios.

**3. Series Temporais (Pandas):** Conversao de timestamps, geracao de intervalos de datas, fusos horarios e reamostragem (resampling).

**4. Visualizacao (Matplotlib + Seaborn):** Plots estatisticos (regressao, distribuicao, categoricos), controle refinado sobre graficos e exportacao em PNG.

**5. Automacao e Desenvolvimento (Python):** Scripting, prototipagem rapida, extensibilidade com C/C++ e escalabilidade via chunking.

---

### Prompt 5 — Prompts reutilizaveis para revisao

**Pergunta:** *Crie um conjunto de prompts que eu possa reutilizar para revisar este tema*

**Resposta obtida:**

**Categoria 1 — Fundamentos de Python**
- *Explique a diferenca tecnica entre listas, tuplas, sets e dicionarios em Python, abordando mutabilidade e performance.*
- *Crie um exemplo com a instrucao match (Python 3.10+) para processar diferentes tipos de respostas de uma API.*
- *Como funcionam as expressoes lambda e quando sao preferiveis ao def em fluxos de analise de dados?*

**Categoria 2 — NumPy**
- *O que torna o ndarray do NumPy mais eficiente que listas nativas para operacoes matematicas em larga escala?*
- *Demonstre algebra linear (multiplicacao de matrizes e inversao) e geracao de numeros aleatorios com NumPy.*

**Categoria 3 — Pandas**
- *Diferencie Series e DataFrame, explicando como rotulos de indice facilitam o alinhamento de dados.*
- *Como funciona a logica split-apply-combine no groupby? Calcule media e soma simultaneamente por categoria.*
- *Quais estrategias para dados ausentes (NaN) e como decidir entre fillna ou dropna?*
- *Quais as vantagens de usar Parquet em vez de CSV para grandes conjuntos de dados?*

**Categoria 4 — Visualizacao**
- *Explique a diferenca entre a interface pyplot e a interface Axes no Matplotlib. Quando usar o metodo set()?*
- *Compare relplot, displot e catplot no Seaborn: quando usar cada um em analise exploratoria?*
- *Como usar temas e paletas de cores no Seaborn para melhorar a legibilidade estatistica?*

**Categoria 5 — Desafios Praticos**
- *Descreva o fluxo completo para analisar um CSV de vendas: importacao, limpeza, agrupamento por regiao e grafico com Seaborn.*
- *Como o Pandas facilita series temporais? Explique resampling e conversao de strings em datas.*

> **Dica de Estudo:** Tente responder sem consultar a documentacao primeiro, depois valide com as fontes para checar indexacao, vetorizacao e estruturas de dados corretas.

---

## Tecnologias e Ferramentas

- [NotebookLM](https://notebooklm.google.com) — IA para organizacao e estudo
- [Python 3](https://www.python.org/) — Linguagem principal
- [NumPy](https://numpy.org/) — Computacao numerica
- [Pandas](https://pandas.pydata.org/) — Analise de dados
- [Matplotlib](https://matplotlib.org/) — Visualizacao de dados
- [Seaborn](https://seaborn.pydata.org/) — Visualizacao estatistica

---

*Projeto desenvolvido como parte do desafio **Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM** na plataforma [DIO](https://web.dio.me).*
