# Credit_Score_ML
Projeto de Ciência de Dados para avaliação de crédito

Este trabalho de análise e ciência de dados segue a metodologia CRISP-DM (Cross-Industry Standard Process for Data Mining) e tem como objetivo desenvolver um modelo preditivo para identificar o risco de inadimplência em concessões de cartões de crédito. O objetivo principal é auxiliar o cliente (mutuário) a tomar decisões informadas sobre crédito, com base em variáveis observadas durante a avaliação do crédito.

Etapa 1: Entendimento do Negócio
Nessa etapa inicial, compreendemos o contexto do negócio e estabelecemos os objetivos. Trata-se de um desafio de concessão de cartões de crédito disponibilizado no Kaggle. O objetivo é construir um modelo preditivo que avalie o risco de inadimplência com base em atrasos significativos (igual ou superior a 90 dias) em um período de 12 meses.

Link original do Dataset em: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

Etapa 2: Entendimento dos Dados
Nessa etapa, analisamos os dados disponíveis, que consistem em uma tabela com informações dos clientes. Foram fornecidas 15 variáveis, além da variável resposta que indica o risco de inadimplência. Um dicionário de dados descreve o significado de cada variável.

Além disso, realizamos uma análise exploratória dos dados e utilizamos algoritmos preditivos. Para isso, foram utilizadas as seguintes bibliotecas: pandas, numpy, seaborn e matplotlib.pyplot para a análise de dados, e sklearn para a aplicação de algoritmos preditivos. Foram utilizados algoritmos como RandomForestClassifier e DecisionTreeClassifier, e métricas como confusion_matrix e metrics.

A avaliação dos modelos resultou nas seguintes acurácias:

RandomForestClassifier com 20 árvores: 97,77%
RandomForestClassifier com 10 árvores: 98,03%
DecisionTreeClassifier: 99%
DecisionTreeClassifier com parâmetros customizados com 5 folhas, profundidade 10 e random_state=123: 97%
