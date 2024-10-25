   # Curso Eu ProgrAmo | Analise de Dados em python 🔎📊📈


Bem-vindo ao repositório do meu projeto inspirado no curso "Meus Primeiros Passos em Python" da PrograMaria. Aqui, você encontrará um conjunto de análises práticas que utilizei para aprimorar minhas habilidades em Python, explorando bibliotecas como Pandas, Numpy e Scipy no Jupyter Notebook. O projeto também abrange SQL com DBeaver e SQLite, além de visualizações de dados com matplotlib, seaborn, plotly e Looker, e uma introdução aos conceitos básicos de machine learning.

## Objetivo do Projeto

O foco deste projeto foi realizar uma análise detalhada dos dados fornecidos pela Comunidade de Dados Data Hackers de 2022. As etapas principais incluíram:

- Limpeza de dados incompletos
- Identificação e tratamento de outliers
- Cálculo de correlações entre variáveis
- Criação de novas features
- Consulta a um banco de dados SQLite para integrar dados sobre renda e educação por estado
- Análise da diversidade em relação a gênero, etnia, localização, escolaridade, senioridade e média salarial

### Ferramentas Utilizadas

- **Python**: A linguagem de programação utilizada
- **Bibliotecas**:
  - `pandas`: Para manipulação e análise de dados
  - `numpy`: Para cálculos matemáticos
  - `matplotlib`: Para criação de gráficos
  - `seaborn`: Para visualizações estatísticas
  - `plotly`: Para gráficos interativos
  - `scipy`: FPara funções científicas e estatísticas
  - `sqlite3`: ara manipulação de bancos de dados SQLite
- **Google Colab**: Ambiente de desenvolvimento utilizado
- **Looker Studio**: Para a criação do dashboard interativo

## Estrutura do Código

1. **Carregamento e Análise Inicial dos Dados**
   - Importação de planilhas com pandas
   - Inspeção dos dados
2. **Tratamento de Dados Ausentes**
   - Substituição de valores ausentes por médias e padrões
3. **Análise Estatística**
   - Cálculo de média, mediana e desvio padrão
   - Intervalo de confiança para a média salarial
4. **Detecção e Correção de Outliers**
   - Visualização de outliers com boxplots
   - Ajuste de outliers salariais
5. **Feature Engineering**
   - Geração de colunas adicionais como "Nível" e "Geração"
6. **Consulta SQL**
   - Conexão ao banco SQLite para extração de dados
7. **Análise de Correlação**
   - Análise das relações entre variáveis contínuas e categóricas
8. **Visualização de Dados**
   - Criação de gráficos interativos e estatísticos

## Dados Analisados

Os dados considerados na análise incluem:

- Gênero
- Etnia
- Pessoas com Deficiência (PCDs)
- Localização (dentro ou fora de SP)
- Faixa etária
- Escolaridade
- Senioridade (Pleno, Júnior, Sênior, Pessoa Gestora)
- Média salarial por gênero e etnia

## Principais Resultados

### Gênero e Etnia
- A pesquisa contou com 4.271 participantes: 74,8% homens, 24,7% mulheres e 0,5% não declararam.
- A maioria dos respondentes se identificou como pesooa **branca** (2744 pessoas).

### Distribuição Geográfica
- A maior parte dos participantes reside fora de São Paulo (2.413 pessoas).

### Escolaridade e Salário
- A análise revelou diferenças significativas na média salarial entre gêneros e etnias, considerando escolaridade e senioridade.
