# ProjetoArtigo
Este documento descreve o processo de pré-processamento da base de dados original "brasileirao_serie_a" para gerar os dados preprocessados necessários para análises posteriores e para alimentar modelos de machine learning.

#1. Arquivo Original e Raspagem (processamento1raspagem.ipynb):

O arquivo original contém os dados brutos da competição do Brasileirão Série A.
Este arquivo é processado pelo notebook Jupyter "processamento1raspagem.ipynb", onde os dados brutos são raspados e tratados para gerar o arquivo "serie_a-com-ano.csv".
O arquivo gerado contém os dados estruturados da competição, com informações de cada jogo e respectivo ano.

Segunda Etapa de Pré-processamento (processamento2MediaeSaldo.ipynb):

#2. O arquivo "serie_a-com-ano.csv", resultante da etapa anterior, é processado pelo notebook Jupyter "processamento2MediaeSaldo.ipynb".
Neste processo, são calculadas médias e saldos relevantes para cada time ao longo dos anos da competição.
O arquivo final gerado por este processo é o "dados_Preprocessados.csv", que é utilizado como entrada para os modelos de machine learning.


Instruções de Uso:
Garanta que você tenha Python e Jupyter Notebook instalados em seu ambiente.
Execute o notebook "processamento1raspagem.ipynb" para realizar a raspagem e tratamento inicial dos dados brutos, gerando o arquivo "serie_a-com-ano.csv".
Em seguida, execute o notebook "processamento2MediaeSaldo.ipynb" para calcular médias e saldos e gerar o arquivo final "dados_Preprocessados.csv".
Utilize o arquivo "dados_Preprocessados.csv" como entrada para os modelos de machine learning, como Random Forest (RF), XGBoost e LightGBM.
