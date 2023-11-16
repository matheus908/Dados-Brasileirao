## Dados do campeonato brasileiro

### Etapas
* Objetivo/Pergunta
* Busca e importação dos dados
* Limpeza dos dados
* Tratamento e transformação dos dados
* Criação da apresentação
* Links do código

#### Tenologias utilizadas:

* Power Point
* Pyspark
* SQL
* DataBricks
* Python

### Objetivo:
#### Criar uma apresentação que responda as seguintes perguntas:
* o que explica as vitórias no futebol, além dos gols?
* o que faz os gols acontecerem no futebol?
* quais fatores levam a uma maior possibilidade de vitória?

### Busca e importação dos dados:
Foram utilizados 4 conjuntos de dados da Kaggle, com dados do da série A do campeonato brasileiro de futebol masculino, de 2003 a 2022.
Dados vieram no formato csv e foi feita a importação através do Databricks, como mostra a imagem abaixo:

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/05ce3f73-b95f-4add-a99b-3c890df83ec1)


### Limpeza
A parte de limpeza foi feita através da análise do objetivo dos dados, por isso fazendo uma análise exploratória, notou- se que nos 4 conjuntos de dados, algumas colunas estavam sem informações dos anos 2003 até 2014, por isso para trabalharmos com dados completos, reduziu- se o período de análise de 2015 até 2022.

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/70984aa0-3d31-4cc4-a6f7-ca65533ae762)


### Tratamento e transformação dos dados
Já que os dados vieram de um arquivo csv, foi feita a conversão dos tipos de dados de todas as colunas, para os tipos mais adequados,nos 4 conjuntos de dados: 
FatoBrasileiraoResultado, DimBrasileiraoEstatisticaFull, DimBrasileiraoGols, DimBrasileiraoCartoes.
* Colunas de numero de gols/chutes etc - integer
* Colunas de data - tipo Date
* Colunas de características - tipo texto
* Colunas de percentual - decimal(5,2)
* colunas de média - decimal(5,2)

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/72bfd263-9e34-474f-812c-dbddd28ff660)


### Análise
Para uma melhor anãlise, criei uma tabela única contendo todos os dados necessários agrupados por clube

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/0530b4f3-413a-4d34-b91f-6c5149780fb1)


### Criação da apresentação

##### Roteiro

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/b0049c3a-d952-43f6-a97c-fb9c0f42f5bb)

##### Reforçando o Objetivo e perguntas

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/93342a41-1e7a-4ecc-b439-452934d8ec5d)

##### Análise e Insights
![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/97dcd9e4-df0d-471b-9fb6-e630b72cb3d6)

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/af9d80a3-bd5f-40f2-ba60-d4cd715ddb66)

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/25e49d24-e2c5-45cc-a5d6-9fa2142d1a35)

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/20523aca-f428-4d4b-9c48-7abd917dbe72)

##### Conclusão

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/7e976b42-257e-4334-a35f-eefb6a40399c)

##### Recomendações

![image](https://github.com/matheus908/Dados-Brasileirao/assets/60456455/e3a0b713-9900-437f-b5b8-626fcf1322b2)

### Link do código

##### Código: 
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3820285923208374/2897594444959936/7208511417105602/latest.html

##### Apresentação:
Fazer download do arquivo Apresentaççao Dados Brasileirão.pptx














