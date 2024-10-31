# Oficina de Ciência de Dados

## Descrição
O projeto tem como objetivo realizar uma análise de sentimento dos usuários em relação a um produto ou marca, utilizando o dataset Sentiment140 do Kaggle.

## Estrutura do Projeto
O projeto está organizado em seções para facilitar a execução e compreensão das etapas de análise:

### Introdução
O projeto começa com uma introdução sobre ciência de dados e expectativas para a análise de sentimentos.

### Dataset Sentiment140
O dataset contém tweets rotulados com sentimentos positivos e negativos.

**Colunas Principais**:
- `target`: Polaridade do tweet (0 = negativo, 4 = positivo)
- `date`: Data do tweet
- `user`: Nome do usuário
- `text`: Conteúdo do tweet

### Pré-processamento de Dados
Limpeza e transformação dos textos para remover URLs, menções, hashtags e caracteres especiais.

### Tokenização e Remoção de Stopwords
Uso da biblioteca NLTK para tokenização e remoção de palavras irrelevantes.

### Visualização de Dados
Diversos gráficos foram criados com Seaborn e Matplotlib, incluindo gráfico de barras, histograma, gráfico de linha e nuvem de palavras, para analisar a distribuição e variação dos sentimentos.

### Estatística Descritiva
Cálculo de estatísticas descritivas e um teste de hipótese para verificar a relação entre o comprimento dos tweets e os sentimentos expressos.

### Modelagem
Aplicação de técnicas de Machine Learning com TF-IDF e algoritmos como Naive Bayes, Regressão Logística e MLPClassifier para classificação dos sentimentos dos tweets.

## Tecnologias Utilizadas
- **Python**: Linguagem principal para análise e modelagem.
- **Pandas e NumPy**: Manipulação de dados.
- **NLTK**: Processamento de linguagem natural.
- **Seaborn e Matplotlib**: Visualização de dados.
- **SciPy e scikit-learn**: Estatísticas e modelagem de machine learning.

## Como Executar o Projeto
1. Clone este repositório.
2. Baixe o dataset Sentiment140 do [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140).
3. Execute o arquivo.
