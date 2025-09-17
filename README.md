### Análise de Sentimento em Avaliações de Filmes
Este projeto teve como objetivo realizar uma análise de sentimento em um conjunto de dados de 50.000 avaliações de filmes. O processo incluiu a limpeza dos dados e a análise exploratória para entender a distribuição de opiniões. O foco principal foi identificar as palavras-chave que diferenciam as avaliações positivas das negativas. Para isso, foram utilizadas as bibliotecas Pandas, Matplotlib e Seaborn na linguagem de programação Python.

###Insights da Análise Exploratória (EDA)

A primeira etapa da análise revelou que o conjunto de dados de avaliações está bem equilibrado. Após a limpeza e o tratamento de dados duplicados, o dataset ficou com 49.988 registros, com a seguinte distribuição de sentimentos:

Aproximadamente 25.000 avaliações positivas.
Aproximadamente 24.700 avaliações negativas.

Essa distribuição quase equitativa permitiu uma análise imparcial da linguagem utilizada em cada tipo de avaliação, sem o viés de uma categoria predominante.

###Análise de Texto e Palavras-Chave
A análise de frequência de palavras foi crucial para extrair insights mais profundos. Os gráficos de barras horizontais criados a partir das 20 palavras mais comuns em cada categoria revelaram diferenças significativas:

Avaliações Positivas:
As palavras mais comuns foram "film", "good", "great" e "story". É notável que o termo "film" teve uma frequência significativamente maior do que "movie" neste contexto. Isso sugere que a palavra "film" tende a ser associada a avaliações mais positivas ou críticas de filmes.

Avaliações Negativas:
Em contrapartida, as palavras mais frequentes foram "movie", "bad", "don't" e "would". A alta frequência de "movie" aqui, combinada com a de "bad" e "don't", indica que este termo pode ser preferido em um contexto mais casual ou de insatisfação direta.

Este projeto demonstrou que a análise de dados pode ir além de simples contagens para revelar nuances importantes sobre o comportamento do público. A diferença no uso dos termos "film" e "movie", por exemplo, serve como um poderoso insight sobre a percepção de qualidade do público. As descobertas reforçam a importância de uma análise textual aprofundada para extrair valor de dados não estruturados. O projeto foi uma demonstração prática das etapas de um ciclo de análise de dados, desde a limpeza inicial até a visualização final de insights.


**Fonte dos Dados:** [IMDB Dataset of 50k Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)