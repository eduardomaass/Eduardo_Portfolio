# [Projeto 1: Investimentos - Fronteira Eficiente](https://github.com/eduardomaass/Investimentos/blob/main/Fronteira%20Eficiente.ipynb)

* A composição da carteira de investimentos é uma dúvida tanto de investidores iniciantes, de pequena escala, quanto de diretorias de grandes empresas. A vasta quantidade de ativos financeiros disponíveis chega a assustar e pode dificultar na escolha de quais ativos farão parte da carteira, e em qual proporção. 

* Uma das respostas para essa dúvida é conhecida como Teoria Moderna do Portfólio, idealizada por Markowitz. Essa teoria relaciona os retornos esperados, riscos e covariação dos ativos componentes da carteira com o objetivo de maximizar o retorno do portfólio para um determinado nível de risco.

* O presente projeto tem como objetivo encontrar a Fronteira Eficiente, uma representação gráfica das carteiras otimizadas através da Teoria Moderna do Portfólio. Para isso, foram consideradas as cotações históricas do ano de 2021 para todos os ativos, extraídas do site Yahoo Finance, e a taxa SELIC do último dia útil de 2021.

* A manipulação dos dados foi feita utilizando as bibliotecas Pandas e Numpy. Os gráficos foram gerados utilizando as bibliotecas Matplotlib e Seaborn.

![](/images/Fronteira_Eficiente.png)



# [Projeto 2: NBA Shots 2020-2021](https://github.com/eduardomaass/NBA-Shots-2020-2021)

* Durante a década de 2010 a NBA passou por uma revolução de dados e estatísticas. Cada vez mais estão sendo utilizados indicadores que mostram o impacto das decisões dos jogadores sobre o resultados final das partidas. Um reflexo dessa revolução de dados é o aumento dos arremessos de 3 pontos. Embora a probabilidade que um desses arremessos seja convertido seja menor, o ponto extra cria uma vantagem quando comparado aos demais tipos de arremesso. Uma forma de medir o quão bom é um arremesso é o Effective Field Goal Percentage (efg), uma medida que representa a porcentagem de arremessos convertidos de um jogador, aplicando um peso maior aos arremessos de 3 pontos devido ao ponto extra.

* O presente projeto tem como objetivo relacionar a medida Effective Field Goal Percentage (efg) com o número de arremessos de cada jogador. De uma forma geral, quanto maior for o efg mais valioso é um arremesso do jogador. 

* Os dados e as fotos do jogadores foram extraídos com Python, utilizando as biblioteca nba_api e Pandas. A manipulação dos dados foi feita utilizando SQL e a visualização foi feita no Tableau.

* Os logos dos times funcionam como botões de filtro, basta clicar em cima de um deles e o dashboard reorganizará os dados de forma a mostrar somente os jogadores do time.

* [O dashboard pode ser acessado no seguinte link](https://public.tableau.com/app/profile/eduardo.maass/viz/NBAEfficiency2020-2021/Dashboard-NBAEfficiency2020-2021?publish=yes)

![](/images/NBA_Efficiency_2020_2021.png)
