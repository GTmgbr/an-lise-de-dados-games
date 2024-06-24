# Projeto de análise de dados sobre a Venda de videogames no cenário mundial

A análise utilizou as bibliotecas pandas e seaborn do Python.

A dupla decidiu, em consenso, optar pelo tema de vídeo games, visto que é um assunto pelo qual temos interesse em nossa vida pessoal, mas também pois é algo extremamente atual e relacionado não apenas com a matéria em específico, mas também com o nosso curso como um todo.

  A coleta foi realizada através do site kaggle.com, que disponibiliza datasets sobre os mais variados assuntos. O dataset específico utilizado para este trabalho foi o vgsales.csv.

## 📌 Organização

A organização dos dados ocorreu da seguinte maneira:

•Separaram-se os dados através dos seguintes critérios:
1) Rank (Posição no ranking de vendas)
2) Name (Nome do jogo)
3) Platform (Plataforma utilizada)
4) Year (Ano de publicação)
5) Genre (Gênero do jogo)
6) Publisher (Produtora responsável pelo jogo)
7) NA_Sales (Vendas na América do Norte)
8) EU_Sales (Vendas na Europa)
9) JP_Sales (Vendas de Japão)
10) Other_Sales (Vendas no Resto do Mundo)
11) Global_Sales (Vendas totais mundiais)

•Lista de dados tratados: - Foram informados os tipos de cada dado, bem como suas respectivas quantidades; - Foram retiradas as linhas que não possuíam valores de vendas globais; - Foram retiradas as linhas com valores nulos; - Foram calculadas as médias de venda para cada região, além das vendas globais.

•Limpeza de dados: - Os dados de vendas foram agrupados em listas para que ficasse mais fácil trabalhar com elas e plotar os gráficos. Uma lista foi criada contendo as vendas da América do Norte, Europa e Japão. Já a outra, contém todos os tipos de vendas; - A variável "anos_vendas" representa o agrupamento do número de vendas totais por anos; - A variável "plataformas_vendas" representa o agrupamento do número de vendas totais por plataforma; - A variável "genero_vendas" representa o agrupamento do número de vendas totais por gênero.
