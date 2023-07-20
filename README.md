# Portfolio_Data_Science
Portfólio para Ciência de Dados e áreas correlatas.
Neste projeto, abordaremos um projeto dividido em 2 etapas: A primeira etapa será apresentado um notebook feito em python para estruturar dados, oriundos de um software de química quântica, em formato de DataFrame para ser utilizado na análise de dados e treinamento de modelos de Machine Learning. E a segunda etapa será feito um modelo de classificação utilizando modelos de Machine Learning com os dados do DataFrame da primeira etapa.

Este é um projeto de ciência de dados com foco na classificação de interações químicas covalentes ou não covalentes aplicados a biomoléculas. O objetivo principal é desenvolver um modelo de classificação de regressão logística capaz de distinguir entre esses dois tipos de interações químicas. Essa classificação é essencial no campo da Dinâmica Molecular e na bioquímica, pois desempenha um papel crucial na produção de fármacos e drogas ou no estudo de doenças e vírus.

# Contexto:

A produção de fármacos e drogas é uma área fundamental na indústria farmacêutica. Compreender as interações químicas que ocorrem entre proteínas e outras moléculas é fundamental para o desenvolvimento de novas terapias e medicamentos. Essas interações podem ser classificadas em dois tipos principais: covalentes e não covalentes. A classificação correta dessas interações pode fornecer informações valiosas sobre a atividade e a eficácia potencial de uma molécula em relação a um alvo específico.

# Objetivos:

O objetivo principal deste projeto é criar um modelo de classificação de regressão logística que possa prever se as interação químicas dos átomos dos proteína são covalentes ou não covalentes. Ao atingir esse objetivo, o modelo pode ser usado como uma ferramenta auxiliar no processo de desenvolvimento de fármacos e drogas futuramente. Desse modo, poderá ajudar os pesquisadores a identificar rapidamente o tipo de interação envolvida e direcionar seus esforços para as moléculas mais promissoras.

# Desenvolvimento:

O desenvolvimento do modelo de classificação de regressão logística para este projeto de ciência de dados envolve as seguintes etapas:

# Pré-processamento de Dados:

Os dados coletados precisam ser preparados para o treinamento do modelo. Isso envolve a limpeza dos dados, tratamento de valores ausentes, normalização ou padronização de recursos e a divisão adequada do conjunto de dados em conjuntos de treinamento e teste. Para isso, será necessário utilizar os arquivos:

# Script_CPprop_txt_Mwfn.ipynb, 
que tem como função estruturar os dados do arquivo 'Cpprop.txt' em um formato de tabela DataFrame, que conterá as informações físicas e químicas dos átomos da molécula de estudo. Esse notebook será de grande valia, pois com a organização dos dados poderemos fazer uma análise de dados e treinar modelos de machine learning, que é o objetivo deste projeto.

Posteriormente, serão gerados 5 arquivos .csv oriundos do código Script_CPprop_txt_Mwfn.ipynb:
# CPprop_svp_b3lyp.csv
# CPprop_tzvp_b3lyp.csv
# CPprop_tzvpp_b3lyp.csv
# CPprop_qzvp_b3lyp.csv
# CPprop_qzvpp_b3lyp.csv

Esses arquivos serão usados para treinar o modelo de classificação.

# Treinamento do Modelo:

O modelo de regressão logística é treinado usando o conjunto de dados de treinamento preparado anteriormente. Durante o treinamento, o modelo aprenderá a mapear as características das interações químicas para suas respectivas classes de covalente e não covalente.
Para isso utilizaremos o arquivo

#Classificacao_interacoes_quimicas.ipynb
que conterá o modelo de classificação de regressão logistica

# Avaliação do Modelo: 

Após o treinamento, é importante avaliar o desempenho do modelo usando o conjunto de dados de teste. Métricas de desempenho, como acurácia, precisão, recall e F1-score, são calculadas para medir o quão bem o modelo está realizando a classificação.

# Resultados:

Os resultados esperados deste projeto são um modelo de classificação de regressão logística que seja capaz de prever com precisão se as interação química dos átomos de uma proteína são covalentes ou não covalentes. O modelo pode ser integrado a fluxos de trabalho existentes no campo da bioquímica, auxiliando na seleção de candidatos promissores para o desenvolvimento de fármacos e drogas.

# Considerações Finais:

Este portfolio de ciência de dados demonstra uma pequena aplicação de um modelo de classificação de regressão logística no campo da bioquímica. A classificação precisa das interações químicas como covalentes ou não covalentes pode ter um impacto significativo no seu estudo futuro de desenvolvimento de fármacos e drogas. Além disso, este projeto ilustra o processo geral de desenvolvimento de modelos de ciência de dados, desde a coleta de dados até a implantação do modelo final.
