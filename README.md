# cblol-esports-2022
Usando os dados deste dataset, construi(ndo) uma base de dados em SQL apenas da divisão brasileira de League of Legends (CBLOL) e organizando os dados, separando em tabelas diferentes.

* 2022_LoL_esports_match_data_from_OraclesElixir.csv \
  É a base de dados primária, ela engloba os dados crus de todos os jogos, de todas as ligas de League of Legends no ano de 2022.
  
* campeoes.csv \
  É a lista relacional dos personagens jogáveis do jogo com seus respectivos id's
  
* construcao_database.ipynb \ 
  É o arquivo em python notebook usado para construir e popular a base de dados em sql

* jogadores.csv \ 
  É a lista relacional dos jogadores profissionais do jogo com seus respectivos id's

* picks_e_bans.csv \ 
  É o aglomerado dos ids dos campeoes banidos e escolhidos por cada lado, relacionados com id's dos campeoes do jogo (campeoes.csv). Cada jogo é identificado por um id único.

* pre_jogo.csv \ 
  É o aglomerado de todas as informações disponíveis antes do jogo: times, escalações e lado de cada time.

* preprocessamento.ipynb \ 
  É o arquivo em python notebook onde foram construidos os arquivos csv simplificados para facilitar a construção da base de dados.
  
* times.csv \
  É a lista relacional dos times que participaram do CBLOL em 2022 com seus respectivos id's

* pos_jogo.csv \
  É o conjunto de dados do jogo concluído

* stats_med.csv \
  É o compilado de estatisticas médias de cada jogador por partida. Por exemplo um valor 0.01 na coluna 'pentakills' significa que em 1% dos jogos o jogador deu um pentakill
