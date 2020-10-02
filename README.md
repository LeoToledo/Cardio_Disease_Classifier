# Cardio_Disease_Classifier

#Neste projeto, iremos analisar o dataset Cardiovascular Disease dataset, extraído do Kaggle: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

###Inicialmente, é realizado um tratamento dos dados, separando, por exemplo, dados categóricos em one-hot vectors. Posteriormente, é feita uma breve análise de correlação entre as features e os labels.

###A seguir, features consideradas menos relevantes são retiradas e features que influenciam indiretamente são combinadas, gerando novas relações. Um exemplo de feature nova criada é o IMC - Índice de massa corporal, que utiliza uma relação entre altura e peso, mostrando-se mais adequado do que apenas essas duas features sozinhas.

###Por fim, utilizando pytorch, é implementada uma MLP para realizar a tarefa de classificação.
