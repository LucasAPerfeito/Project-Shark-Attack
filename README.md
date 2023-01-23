
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
  e sem estrutura, mas com o caminhar da limpeza os resultados e infereências são interessantes. O Dataset apresenta um tamanho temporal gigantesco, tem alguns
  casos que são antes de cristo.
 

# Steps
  1 - Corte dos nulos usando o seaborn e visualizando que mais de 60% dos dados estavam vazios
  2 - A coluna de gênero estava majoritariamente preenchida e seguia um padrão. 
  3 - 89% dos ataques que tinham informações sobre sexo do atacado são homens (11% mulheres)
  4 - Fiz um corte temporal(só casos que aconteceram depois de 1950), por conta dos casos e as informações sobre os casos mais antigos
  5 - 70% dos dados são depois de 1950 e a média da coluna de anos era 1927 então esses casos mais antigos ponderavam para um lado, mas decidi não analisá-los.
  6 - Apesar dos homens serem mais atacados pelos tubarões teve alguns anos que as mulheres foram bem mais atacadas (2007, 2017, 2010, 1993) mais de 20% dos casos anuais foram em mulheres
  7 - Da mesma maneira que tem agluns anos que as mulheres foram mais atacadas tem alguns países que elas são o foco, como Espanha e Egito. 
  8 - Categorizei as atividades em grandes grupos (Surfing, Swimming, Boat, Diving, Fishing, Interating with sharks e outros)
  9 - Proporcionalmente as atividades que menos impactam as mulhreses são pesca, surfe e mergulhando. E a que mais impacta é nadando.
  10 - Nesse ponto 9 proporção tem que ser levado em conta uma vez que em valores absolutos essas ordens são diferentes, porém a natureza da atividade e os ataques são levados em consideração.

# Conclusion
  Os homens são sem duvidas mais atacados por tubarões em quase todas as regiões do mundo, as principais atividades que originam ataques, são surfe, nadar no mar e pesca,
  sobre essas atividades é interessante ver como a atividade de pesca é em grande parte praticada por homens, uma vez que existe a diferença grande nos ataques de acordo 
  com o gênero. Além disso é interessante ver como os ataques as mulheres vêm aumentando nos últimos anos, uma vez que a proporção de ataques pelo gênero vem aumentando.
  Isso pode ser explicado pelas mudanças no ambito do gênero, hoje em dia não as atividades não são mais separadas por gênero e isso é pontuado a partir do aumento 
  dos casos que envolvem mulheres.
  
# Contact
  linkedin: https://www.linkedin.com/in/lucas-perfeito-0a55381ab/ 
  
