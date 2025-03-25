## Projeto sentiment stock
### Problem:
Milk Temperature on the Farm: Ensuring Quality and Safety
The temperature of milk on the farm is a crucial factor in ensuring the quality, safety and shelf life of the product. From milking to storage, temperature control is essential to prevent the proliferation of bacteria and maintain the nutritional properties of milk.

Temperatura do Leite na Fazenda: Garantindo Qualidade e Segurança
A temperatura do leite na fazenda é um fator crucial para garantir a qualidade, segurança e vida útil do produto. Desde a ordenha até o armazenamento, o controle da temperatura é essencial para evitar a proliferação de bactérias e manter as propriedades nutricionais do leite.

### Motivation:
Proper Storage
Chilled milk must be stored in cooling tanks, keeping the temperature below 4°C. It is important to ensure that refrigeration equipment is working properly and that the temperature is monitored regularly.

Armazenamento Adequado
O leite resfriado deve ser armazenado em tanques de resfriamento, mantendo a temperatura abaixo de 4°C. É importante garantir que o equipamento de refrigeração esteja funcionando corretamente e que a temperatura seja monitorada regularmente.

### Solution:
By transferring the temperature data through the Milk_Diagnostic equipment (device for collecting and sending milk data on the farm via SMS), we will analyze this data and use deep reinforcement learning to predict the temperature of the milk in the next few minutes, being able to alert the collecting company about a possible increase and for the producer to take action before the event happens. This guarantees the quality of the milk.

Transferindo os dados de temperatura através do equipamento Milk_Diagnostic (aparelho de coleta e envio de dados do leite na fazenda via sms) vamos analisar esses dados e treinar um modelo de classificação de machine learning para descobrirmos, conforme a variação da temperatura do leite, qual o percentual de um leite estar alterado, com alguma contaminação, alertando tanto o produtor quanto a empresa captadora, para que esse leite não seja misturado com os demais de boa qualidade.

### Objective:
- In this project, we will perform a sentiment analysis of data published on X (Twitter), in real time, relating to stock market quotes. This analysis can be passed on to our investors, through sentiment percentages, whether the messages about the quotes present a positive or negative trend for the subject in question.

- Nesse projeto vamos fazer uma análise de sentimentos de dados publicados no X (twitter), em tempo real, relativo às cotações da bolsa de valores. Essa análise vai poder passar para nossos investidores, através dos percentuais de sentimentos, se as postagens sobre as cotações, apresentam uma tendência positiva ou negativa para o assunto tratado.

### Data Origin:
- Dataset: financial_tweets.csv

- This file was acquired by capturing tweets from users who made publications within the subject discussed here, expressing their feelings about stock market quotes in real time. The data is intercepted through an API provided by X (twitter) and saved in a .csv file.

- Esse arquivo foi adquirido através da captura de tweets dos usuários que fizeram publicações dentro do assunto aqui tratado, expressando seus sentimentos sobre cotações da bolsa em tempo real. Os dados são interceptados através de API fornecida pelo X (twitter) e gravados em arquivo .csv.

Aqui o que nos interessa é somente o campo:
Description: descrição do sentimento publicado pelo usuário.