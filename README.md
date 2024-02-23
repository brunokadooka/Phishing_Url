# Phishing_Url

Este repositório é para praticar e aprimorar habilidades em análise de dados, focando em tratamento de valores ausentes, identificação de outliers, limpeza de dados, análise exploratória, análise descritiva e um pouco de machine learning. Uso Pandas, NumPy, Matplotlib e Seaborn para desenvolver notebooks que demonstram minha evolução nessas áreas, este tambem é um projeto todo comentado para mostrar as decisões que tomei ao longo do desenvolvimento, além tudo este repositório foi para estudar **problemas de CLASSIFICAÇÃO.**

Alguns conhecimentos estudados e abordados neste projeto foram:

 - Análise de dados e Análise Exploratória (Identificação e tratamento de dados ausentes, duplicados e outliers);
 - Análise Descritiva (Visualização e discussão a respeito das features, relevância, correlações, WOE e Information Value);
 - Modelagem (Validação Cruzada, Pipelines, Tecnicas de *Sampling* e *scaling*, Busca de Hiperparametros com a busca de otimização Bayesiana, KNN, Decision Tree, Random Forest e XGBoost);
 - Vimos na prática alguns conceitos de treino e teste;
 - Trabalhar com dataset's com longo tempo de execução (Paralelização com Threads, e Dividir o problema).

## Sobre o projeto

Este projeto visa identificar através da URL se o site pode ser Phishing ou não. Neste projeto para estudar a parte de Análise de Dados e Modelagem contamos com um dataset menor, um pouco mais de 2 mil registros. Mas também tivemos o curiosidade de verificar como os modelos treinados em pouco dado se sairia em relação a um dataset maior, deste modo, procuramos outro dataset um com 550 mil registros.

Deste modo o projeto conta com dois dataset's, o primeiro e o menor utilizamos para estudar o conteúdo de Análise e Modelagem, visto que o tempo para tratamento e treinamento seria mais curto, e assim não atrapalharia os estudos. O segundo dataset com maior registros tambem teve desafios como inserir features novas, como possui muitos registros e uma das features tinha o *timeout* de 1 segundo (feature: *valid_url* ela verifica se a URL está ativa ou não, por isso dependia do tempo de resposta do site, que era no máximo de 1 segundo), deste modo, era necessário abordar novos conceitos como de Threads para agilizar a etapa.

Outras motivações do porque utilizamos os dataset's estão no primneiro notebook, de visão geral.
