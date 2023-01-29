
# Project Name
  Status(Active)
# Project objective
  O objetivo do projeto é utilizar o Dataset de atques de tubarão disponibilizados no Keagle, botar em prática ferramentas de Data Cleaning e partir 
  dessa limpeza analisar e tirar algumas inferências sobre ataques de turbarão. Ja dando um spoiler sobre as minhas inferências, fiz uma análise em cima
  do gênero das pessoas que eram atacadas por tubarões. Queria saber a preferencia dos tubarões sobre o gênero dos ataques, os anos que esses ataques mais
  ocorriam e por fim, qual atividade as pessoas estavam fazendo antes de serem atacadas, sempre colocando os gêneros em comparação.
# Methods

  List with methods:
  - Visualização de nulos
  - Limpeza de Dados
  - Filtrar os dados
  - Agrupar
  - Categorizar dados
# Technologies 
  - Python
  - Pandas
  - Seaborn
# Project Description
  Incialmente o Dataset possuí cerca de 25.500 linhas e 24 colunas, porém com a ajuda do seaborn vizualiamos que mais de 60% das linhas estão completamente
  vazias, assim como duas colunas. Então retiramos essas linhas e colunas do Dataset e ficamos com cerca 6.300 linhas e 22 colunas. A maioria dessas colunas
  são colunas com informações demográficas sobre os ataques, informações sobre as fontes do caso e dados temporais. Inicialmente os dados estão bem bagunçados
  e sem estrutura, mas com o caminhar da limpeza os resultados e infereências são interessantes. O Dataset apresenta um tamanho temporal gigantesco, tem casos relatados antes do nascimento de cristo até o ano de 2018.
 

# Steps
  1. Visualização gráfica das colunas e linhas preenchidas utilizando a biblioteca seaborn.
  2. Os nulos ocupavam mais de 60% do Dataframe, assim foram retiradas colunas sem pelo menos 70 linhas preenchidas e linhas sem dados em pelo menos 5 colunas.
  3. Como queria fazer uma análise majoriatariamente sobre gênero, comecei analisar, limpar e entender a coluna 'sex'. 
  3. Depois de toda limpeza e tratamento da coluna sex a proporção de gênero era de que a cada 10 ataques de tubarão 9 eram homenas e apenas 1 era mulher.
  4. Para entender melhor essa disparidade comecei a analisar a coluna de 'year'.
  5. Os dados de ano tinham uma amplitude gigantesca, dados desde antes de cristo até 2018.
  6. Para mim os dados recentes eram mais interessantes, entao notei que 70% dos dados são depois de 1950, assim fiz um corte temporal e decidi utilizar apenas os casos da década de 50 até 2018.
  7. Depois da limpezas nos anos, agrupei os casos por anos e separei os ataques por gênero e vi que apesar dos homens serem mais atacados pelos tubarões, teve alguns anos que essa proporção era diferente.
  8. Depois de ter analisado por anos, queria ver se os países tinham influencia sobre os atques sobre as mulheres.
  9. A relação sobre os países é baixa, porém tem alguns países que apenas mulheres foram atacadas, mas o número de ataques registrado nesses países é relativamente baixo como Espanha e Egito. 
  10. Por fim queria ver se as atividades que cada gênero praticava no momento em que os ataques aconteceram.
  11. Para analisar esse efeito, categorizei as atividades em grandes grupos (Surfing, Swimming, Boat, Diving, Fishing, Interating with sharks e outros)
  12. Percebi uma disparidade na proporção de atividades que homens e mulheres estavam praticando no momento em que foram atacados.
  13. Proporcionalmente as atividades que menos impactam as mulhreses são pesca, surfe e mergulhando. E a que mais impacta é nadando. Enquanto os homens são impactados surfando e pescando.
  14 - Só para fortalecer o ponto 13 é importante lembrar que os valores absolutos de cada atividade apresentam uma ordem diferente, mas a porporção é a que foi utilizada e levada em consideração.

# Conclusion
  Os homens são sem duvidas mais atacados por tubarões em quase todas as regiões do mundo, as principais atividades que originam ataques, são surfe, nadar no mar e pesca,
  sobre essas atividades é interessante ver como a atividade de pesca é em grande parte praticada por homens, uma vez que existe uma grande diferença nos ataques feito as mulheres pescando. 
. Além disso é interessante ver como os ataques as mulheres vêm aumentando nos últimos anos, uma vez que o número de ataques estão se equalizando independente do gênero.
 Hoje as atividades/esportes não apresentam mais barreiras em relação a sexo, assim é comum ver mulheres se aventurando mais e praticando atividades/esportes que antes eram centralizadas e comercializadas sobre o sexo masculino.
  
# Contact
  Linkedin: https://www.linkedin.com/in/lucas-perfeito-0a55381ab/ 
  
