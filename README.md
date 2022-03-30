# Predição de preço das casas usando técnicas de regressão:

## Introdução:

Meu terceiro projeto de machine learning em que faço a competição "House-Prices---Advanced-Regression-Techniques" do Kaggle que fica hospedada no link abaixo:

https://www.kaggle.com/c/house-prices-advanced-regression-techniques

Nessa competição o objetivo é prever o valor de casas a partir de um conjunto de features que descrevem as características de cada habitação.

## Desenvolvimento:

Durante o projeto tive a oportunidade de aplicar os conceitos de análise e limpeza dos dados, além do treinamento e teste de diversos modelos de regressão. Após escolher o melhor modelo, usando validação cruzada, encontrei os melhores parâmetros e com eles realizei a predição do preço das casas na base de teste

## Resultados encontrados e conclusões

Model               |    RSME    |    MAE   	| R2
--------------------|------------|------------|-----
Linear              |34292.066172|21217.245255|0.808654
Lasso               |34243.797211|21191.725763|0.809185
Ridge               |34070.441706|21116.614448|0.811113
Elasticnet          |39791.169440|24855.853127|0.743116
Randomforest        |31483.863407|19029.278348|0.838903
XGB                 |31962.883473|19172.211020|0.833317
AdaBoost            |37896.862435|25975.591471|0.765959
KNeighbors          |39546.658734|24587.140876|0.744340
RandomForest_Tunning|30408.801632|17888.823232|0.850387
XGB_Tunning         |30632.237645|18273.112651|0.848139
