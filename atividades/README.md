##Atividade - Machine learning
Grupo: Alessandro Feitosa Jr, Bianca Muniz, Jéssica Avelar, Renan Cavalcante, Ricardo Grinbaum, Vinicius Marques

Proposta: Elencar pelo menos 6 possibilidades de modelo para classificação ou regressão e 2 para segmentação. (8 no total)

1. Modelo para ver as chances de derrota, empate e vitória de um jogo do campeonato brasileiro de futebol
Base de dados a serem utilizadas: bases obtidas com o pacote {brasileirao}, do R
Variáveis explicativas: Quantidade de gols, resultado (vitória/derrota ou empate), se o time vitorioso é visitante ou não
Utilidade do modelo: fundamentar apostas e estratégias para jogadores e equipe técnica dos times

2. Modelo para segmentar, a partir dos votos, os grupos de votação na câmara e no senado.
Base de dados a serem utilizadas: As bases de votação da Câmara de 2019 a 2021 e de votação do Senado
Variáveis explicativas: nome do político, partido, votações anteriores
Utilidade do modelo: entender sobre os partidos/políticos, as diferenças entre as casas e as posições partidárias.

3. Modelo para prever a qualidade do ar em São Paulo
Bases de dados a serem utilizadas: previsão do tempo, dados de tráfego, tamanho da frota de carros
Variáveis explicativas: falta de chuva e de vento; maior volume de carros, seja pela época do ano ou pelo desempenho da economia
Utilidade do modelo: prever políticas públicas para os dias de pior qualidade do ar; entender qual é a dimensão do problema e discutir medidas estruturais 

4. Modelo para prever a evolução dos acidentes com motos em São Paulo
Bases de dados a serem utilizadas: dados de movimento do trânsito, dados de chamadas nos serviços de entrega, histórico de acidentes
Variáveis explicativas: horários de pico no serviço de entrega, velocidade média nas principais vias, aumento do número de entregadores
Utilidade do modelo: mapear a evolução e os horários de maior número de acidentes para desenvolver políticas públicas para reduzir o número de casos

5. Modelo de segmentação de leitores de um site de notícias
Base de dados a serem utilizadas: dados de visitas ao site; dados de assinaturas do site
Variáveis explicativas: perfil dos visitantes (tempo médio de visita, só dá uma olhada, visitante recorrente), origem do tráfego, estratégia de paywall do site, estratégia de preços do site
Utilidade do modelo: ao segmentar os visitantes do site em tipos de leitores, pode-se desenvolver estratégias específicas para promover a conversão de assinaturas

6. Modelo para prever o desmatamento no Brasil.
Base de dados a serem utilizadas: Dados do DETER, e do Prodes, ambos do Inpe
Variáveis explicativas: região, taxa desmatamento, chuva
Utilidade do modelo: entender a evolução do desmatamento no Brasil, pensar em políticas públicas e adequação aos acordos internacionais.

7. Modelo para prever o próximo hit do carnaval
Base de dados a serem utilizadas: Lista de músicas mais tocadas no Carnaval e bases geradas pela API do Spotify (podem ser baixadas com a biblioteca {spotipy} em Python ou pacote {spotifyr} no R)
Variáveis explicativas: as características de áudio das músicas listadas (key, acousticness, danceability, energy, instrumentalness, liveness, loudness), características dos artistas (estilo musical, gênero)
Utilidade do modelo: a partir do que há de comum nas músicas mais tocadas, pode ser possível imaginar tendências musicais

8. Modelo para prever cidades mais propensas a terem queimadas
Base de dados a serem utilizadas:  BDqueimadas, do Inpe
Variáveis explicativas: Bioma, número de dias sem chuva
