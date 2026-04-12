# MVP Análise de Dados e Boas Práticas

Projeto final da disciplina **Análise de Dados e Boas Práticas** do MBA PUC-RJ em Ciência de Dados.

**Nome:** Lucas Dantas Matos Vidal  
**Matrícula:** 4052025002493  

**Dataset:** [Mental Health - Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/mental-health/data)  
**Versão Google Colab:** [Abrir Notebook](https://colab.research.google.com/drive/14nz9lBWlhzd34Hs8pdQXWZh4ArPBdS0W#scrollTo=cmYX3PLx58Jg)

---

## Mental Health Analysis – EDA e Pré-processamento

### 1. Descrição do Projeto

Este projeto representa o **Minimum Viable Product (MVP)** da disciplina de Análise de Dados e Boas Práticas. O objetivo principal é analisar a prevalência de diferentes transtornos mentais ao longo do tempo e entre diferentes países, buscando identificar padrões, relações e variações nos dados.

Utilizando um dataset público contendo informações sobre transtornos mentais (como ansiedade, depressão, esquizofrenia, transtorno bipolar e transtornos alimentares), o projeto aborda as etapas iniciais de um fluxo de Ciência de Dados, incluindo **Análise Exploratória de Dados (EDA)** e **pré-processamento**, preparando os dados para futuras aplicações de Machine Learning.

---

### 2. Tecnologias Utilizadas

- **Linguagem:** Python  
- **Manipulação de Dados:** pandas, numpy  
- **Visualização de Dados:** matplotlib, seaborn  
- **Pré-processamento:** scikit-learn (conceitos de normalização e padronização)  
- **Ambiente:** Google Colab  

---

### 3. Hipóteses Analisadas

Durante a análise exploratória, foram avaliadas as seguintes hipóteses:

- **Variação Temporal:** A prevalência de transtornos mentais varia ao longo do tempo  
- **Diferença entre Transtornos:** Diferentes transtornos apresentam níveis distintos de ocorrência na população  
- **Comportamento Semelhante:** Alguns transtornos podem apresentar padrões semelhantes ao longo do tempo  
- **Variação Geográfica:** A prevalência dos transtornos varia entre diferentes países  

---

### 4. Principais Insights

A análise dos dados permitiu identificar alguns pontos importantes:

- Transtornos como **ansiedade e depressão** apresentam maior prevalência em comparação aos demais  
- Transtornos como **esquizofrenia e transtornos alimentares** apresentam menor variação e maior estabilidade  
- Não foram identificadas **tendências significativas ao longo do tempo**, indicando estabilidade nos dados  
- Foram observadas **correlações moderadas** entre alguns transtornos, sugerindo padrões semelhantes  
- A análise por país evidenciou **diferenças relevantes entre populações**, indicando influência de fatores externos  

---

### 5. Estrutura do Notebook (.ipynb)

O projeto foi organizado de forma sequencial:

- **Definição do Problema:** Contextualização e objetivo da análise  
- **Carga de Dados:** Importação do dataset  
- **Análise Exploratória (EDA):**
  - Estatísticas descritivas (média, mediana, desvio padrão)
  - Visualizações (histogramas, boxplots e matriz de correlação)
- **Tratamento de Dados:**
  - Verificação de valores nulos e duplicados
  - Remoção de variáveis irrelevantes
- **Pré-processamento:**
  - Criação de novas variáveis (ex: década)
  - Padronização de nomes de colunas
  - Preparação geral dos dados

---

### 6. Considerações Finais

O projeto permitiu compreender melhor o comportamento da prevalência de transtornos mentais em diferentes contextos.

Apesar da ausência de tendências temporais fortes, foram identificadas diferenças importantes entre os transtornos e entre os países, reforçando a complexidade dos fatores que influenciam a saúde mental.

Os dados analisados mostraram-se consistentes e adequados para análise exploratória, servindo como base para estudos mais avançados ou futuras aplicações de modelos preditivos.
