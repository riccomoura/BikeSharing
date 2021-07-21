# Bike Share System
## Operação
O sistema de bike sharing se traduz por aluguel de bicicletas onde o processo de obtenção da assinatura, aluguel e devolução é automatizado através de uma rede de quiosques localizados em diversos pontos de uma cidade.

## Conceito
Utilizando esse sistema, pessoas estão aptas a alugar uma bicicleta a partir de um local e devolvê-las à diferentes locais que necessariamente servem como bases.

## Dados
Os dados gerados por esses sistemas os tornam atraentes para pesquisadores por causa da duração de uma viagem, local de partida, local de entrega e o tempo consumido que é explícitamente registrado. Portanto, o sistema de Bike Sharing (compartilhamento de bicicletas) tem por função a uma rede sensorial que pode ser usada para estudar as condições de mobilidade de uma cidade.
 
## Objetivo do teste
Análise exploratória dos dados obtidos através dos arquivos CSV;
Exibir gráficos com padrões de consumo;
Mostrar correlações de dados como condições climáticas e padrões no histórico de uso das bicicletas a partir das variáveis;
Extra: criar um modelo preditivo para calcular a demanda do serviço afim de sugerir tomada de decisões a cerca do modelo de negócio e sua expansão ou retração futura.
Progressão do desenvolvimento
 ## Etapa 1: Exibição de Dados
 - Importar base de dados
 - Concluir premissas básicas
 ## Etapa 2: Análise e Correlação
  - Exemplo de dado obtido e manipulado em ambos bancos de dados importados. Média da velocidade do vento no período de coleta de dados da plataforma.
  - Métricas de locação
  - Análise Top -> Down. Correlação entre o número total de locações realizadas e a estação do ano
 ## Etapa 3: Exibição de gráficos
  - Importando matplotlib para exibição de gráficos
  - Criando um novo dataframe a partir da Tabela Train
  - Criando o gráfico a partir do novo dataframe
 ## Etapa 4: Conclusões finais ou Modelo Preditivo
  - Durante as estações mais quentes e secas há substancial aumento da demanda
  - Sugere-se maior empenho no marketing com foco em fidelização
