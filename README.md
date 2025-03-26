## Projeto sentiment stock
### Problem:
Not knowing the value of a stock in the stock market can lead to poor investment decisions and significant financial losses. To avoid this, it is important to understand the factors that influence stock prices and how to value them.

Não ter noção do valor de uma ação na operação da bolsa de valores pode levar a decisões de investimento ruins e perdas financeiras significativas. Para evitar isso, é importante entender os fatores que influenciam o preço das ações e como avaliá-las.

### Motivation:
There is no way to know for sure what a stock trader is thinking about the price of a particular stock. The stock market is complex and influenced by many factors, and traders make decisions based on their own analysis and strategies.
If we could listen in on the conversations between stock traders about the price of a stock, we would have access to a valuable, but also complex and potentially confusing, level of information.

Não é possível saber com certeza o que um operador da bolsa está pensando sobre o preço de uma ação específica. O mercado de ações é complexo e influenciado por diversos fatores, e os operadores tomam decisões com base em suas próprias análises e estratégias.
Se pudéssemos ouvir as conversas entre operadores da bolsa sobre o preço de uma ação, teríamos acesso a um nível de informação valioso, mas também complexo e potencialmente confuso.

### Solution:
Twitter has become a thermometer of market sentiment, with traders and analysts sharing their opinions in real time. It is possible to identify trends and reactions to news before they are reflected in prices.
Using NLP (natural language processing) resources together with Python resources, we will capture the tweets, specifically the descriptions of the publications, and we will subject these descriptions to a sentiment analysis, using NLTK resources, to discover the percentage of positive and negative sentiment of the posts.

O Twitter se tornou um termômetro do sentimento do mercado, com operadores e analistas compartilhando suas opiniões em tempo real. É possível identificar tendências e reações a notícias antes que se reflitam nos preços.
Utilizando recursos de NLP (processamento de linguagem natural) juntamente com recursos do python, vamos capturar os tweets, especificamente a descriçao das publicações, vamos submeter essas descrições a uma análise de sentimento, através de recursos de nltk, para descobrirmos o percentual de positivo e negativo do sentimento das postagens.

### Objective:
- In this project, we will perform a sentiment analysis of data published on X (Twitter), in real time, relating to stock market quotes. This analysis can be passed on to our investors, through sentiment percentages, whether the messages about the quotes present a positive or negative trend for the subject in question.

- Nesse projeto vamos fazer uma análise de sentimento de dados publicados no X (twitter), em tempo real, relativo às cotações da bolsa de valores. Essa análise vai poder passar para nossos investidores, através dos percentuais de sentimento, se as postagens sobre as cotações, apresentam uma tendência positiva ou negativa para o assunto tratado.

### Data Origin:
- Dataset: financial_tweets.csv

- This file was acquired by capturing tweets from users who made publications within the subject discussed here, expressing their feelings about stock market quotes in real time. The data is intercepted through an API provided by X (twitter) and saved in a .csv file.

- Esse arquivo foi adquirido através da captura de tweets dos usuários que fizeram publicações dentro do assunto aqui tratado, expressando seus sentimentos sobre cotações da bolsa em tempo real. Os dados são interceptados através de API fornecida pelo X (twitter) e gravados em arquivo .csv.

Aqui o que nos interessa é somente o campo:
Description: descrição do sentimento publicado pelo usuário.