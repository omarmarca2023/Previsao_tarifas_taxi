# Previsão de Tarifas em Corridas de Táxi

Empresas como a Uber estão usando amplamente o aprendizado de máquina para prever tarifas, tráfego e viagens usando dados anteriores.

 ## Problema de Negócio
 
Imagine que você trabalha para uma empresa de táxi e que uma das maiores reclamações de seus clientes é que eles não sabem quanto custará uma corrida até que ela termine.Isso porque a distância é apenas um dos vários fatores a partir dos quais as tarifas de táxi são calculadas.

Você decide fazer algo a respeito criando um aplicativo móvel que os clientes possam usar quando entrarem em um táxi para estimar qual será a tarifa.Para fornecer inteligência ao aplicativo, você pretende usar as enormes quantidades de dados de tarifas que a empresa coletou ao longo dos anos para criar um modelo de aprendizado de máquina.

O conjunto de dados contém cerca de 150000 linhas e é um subconjunto de um conjunto de dados muito maior usado na competição New York City Taxi Fare Prediction da Kaggle.

## O modelo de árvore de decisão mais simple é escolhido como o modelo final para este projeto

Com base na hora do dia, dia da semana e a distância percorrida fornecidos, o modelo pode fazer uma previsão estimada do valor da tarifa.

O modelo está errando mais ou menos 3.03 dólares (RMSE) e 1.95 dólares em termos absolutos (MAE). A variável mais importante para prever a tarifa foi a distância.

Podemos explorar outros algoritmos de aprendizado, como Random Forest e Gradient Boosting, para melhorar a previsão do modelo.
