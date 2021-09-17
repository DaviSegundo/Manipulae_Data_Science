# Análise Manipulaê

## Descrição das Atividades realizadas

### Pré-processamento e Análise

Foi feita uma análise exploratória inicial para avaliar bem como os dados estavam definidos, também foi feita uma verificação da integridade das informações, com o intuito de constatar se haviam dados faltantes.

Houve um processo de feature engineering para criação de novas variáveis que auxiliaram na predição do valor correto do preço das receitas. Uma das principais alterações foi a separação da descrição das receitas.

### Machine Learning

Foram usados dois modelos para o processo de aprendizagem, os quais foram o GradientBoosting e CatBoosting. Assim, no final foi feito um ensemble entre os dois modelos para aprimorar mais ainda a predição. Para chegar no melhor resultado de cada modelo houve um processo de GridSearch para encontrar os melhores parâmetros.

### Validação

Os resultados obtidos foram constantemente incrementados ao longo do estudo dos dados, chegando a mais de 90% de R2_Score, por exemplo. Alguns resultados bem interessantes também foram observados fazendo um avaliação de algumas faixas de valores específicas, como um Erro médio absoluto de aproximadamente R$ 3.00.

## Métricas de avaliação

$$R^2=1-\frac{\textrm{Variância Residual}}{Variância Total}$$
$\\$
$$MSE=\frac{1}{n}\sum_{i=1}^{n}(\hat{y}-y)^2$$
$\\$
$$MAE=\frac{1}{n}\sum_{i=1}^{n}|\hat{y}-y|$$
$\\$
$$RMSE=\sqrt{\frac{1}{n}\sum_{i=1}^{n}(\hat{y}-y)^2}$$
$\\$
$$MAPE=\frac{1}{n}\sum_{i=1}^{n}|\frac{y-\hat{y}|}{y}$$



