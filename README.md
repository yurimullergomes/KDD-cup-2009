# KDD-cup-2009
Classificador de comportamentos de clientes a partir de dados do tipo customer relationship management (CRM)


## As seguintes etapas foram implementadas:


* Prepararemos os dados, retirando as variáveis indesejáveis;
* Aplicaremos o 'up-sampling' na parte dos dados subrepresentada;
* Treinaremos o classificador "RandomForestClassifier" com os dados;
* O valor da AUC utilizando o método de k-fold com k = 5;
* A matriz de confusão do classificador (comum e normalizada);


Por fim, obtivemos os seguintes resultados:
* ## ``AUC para 'upselling' : 0.80 +/- 0.05 ``

* ## ``AUC para 'appetency' : 0.69 +/- 0.09``

* ## ``AUC para 'churn' : 0.84 +/- 0.07``

Portanto temos:

## ``AUC_médio = 0.77 +/- 0.04``
