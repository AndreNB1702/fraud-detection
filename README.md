# fraud-detection

Project detecting fraud with Machine Learning - Artificial Intelligence - Universidade Federal de Rondônia

English:
In this project, I used Boosting Models and compared to Baseline Models.

analysis.ipynb: contains the exploratory analysis of the dataset. It was found that
It was found that transactions considered fraudulent are of the ‘CASH_OUT’ and ‘TRANSFER’ types.
There is no correlation between the time the transaction took place and the fact that it was fraudulent.
Of the transactions that are fraudulent, in 98% of them, the account from which the transaction originated is left with no money.

log_reg.ipynb: I used techniques until I found a good model.
I explored undersampling, k-folds, and class weights.
When using class weights, I achieved the best recall (97.50%), but the accuracy was low (3.56%).
When using undersampling, I achieved good recall (88.68%) and slightly better accuracy (11.21%).

Português:
Nesse projeto, eu usei Modelos de Boosting e comparei com Modelos Baseline.

analysis.ipynb: contém a análise exploratória do dataset.
Foi encontrado que as transações consideradas fraudes são do tipo 'CASH_OUT' e 'TRANSFER'.
Não há uma correlação entre o horário que aconteceu a transação com o fato dela ser fraude.
Das transações que são fraudes, em 98% delas, a conta de origem da transação fica sem dinheiro.

log_reg.ipynb: usei técnicas até encontrar um bom modelo.
Explorei undersampling, k-folds, class weights.
Ao usar class weights, atingi o melhor recall (97,50%), mas a precisão estava baixa (3,56%).
Ao usar o undersampling, consegui um bom recall (88,68%) e uma precisão um pouco melhor (11,21%).
