# Data Science Aplicada - Bootcamp Alura

# Introdução:
Analisar e levantar hipósteses sobre o impacto de óbitos que ocorreram por covid na cidade de São Paulo em relação ao total de óbitos por causas gerais na mesma cidade.
 

# Desenvolvimento:
Para isso vamos baixar os dados disponibilizados no DATASUS (https://datasus.saude.gov.br/) para obtermos os dados por mortes no geral, e os dados no portal Corona Virus Brasil (https://covid.saude.gov.br/) para obtermos os dados por morte devido ao corona vírus. Esses dados sobre a covid foram alimentados pelas Secretarias Estaduais de Saúde, e separados por dia, no período de março de 2020, mês que ocorreu o primeiro óbito por covid, até novembro de 2021 (última atualização). Já os dados de mortes em geral alimentados pelo SUS, são do período de Janeiro de 2008 até Setembro de 2021 (última atualização). Dessa forma, analisaremos os dados no período de Março de 2020 até Setembro de 2021 para realizar nosso trabaho.
Os dados foram tratados de forma separada, e ao final foi feito um merge entres as informações para obtermos o resultados desejados.


# Conclusão:
Com as informações acima, podemos levantar as seguintes hipóteses:

* A infecções por Covid causaram um grande impacto no número geral de óbitos durante essa pandemia em São Paulo. Em alguns meses, o percentual de óbitos chegou a mais de 25% em relação ao total de óbitos por causas gerais, como podemos observar em abril de 2021.
* Outra hipótese levantada, é comprovar a eficácia da vacina na população, já que no último mês (última atualização), setembro de 2021, o percentual de óbitos por covid caiu para 9,40%.
* No gráfico de colunas empilhadas podemos observar com mais clareza a proporção de óbitos por covid em relação aos óbitos gerais.
* Em média geral, as infecções por covid foram responsáveis por 13,41% das mortes em São Paulo no período de 03/2020 até 09/2021.
* No gráfico de barras empilhadas, podemos verificar claramente que ouveram 2 ondas de infecção, em que a segunda onda começou a ganhar força em março de 2021, e começou a regredir em maio de 2021, provavelmente devido ao resultado da vacinação.

O trabalho realizado e as hipósteses lenvantadas, poderiam ser mais precisos caso as informações de óbitos informados pelo DATASUS através do TABNET, fossem computados no dia exato da morte ao invés do dia do processamento, já que o paciente pode ter entrado em óbito no mês atual, e o processamento desse óbito ser concluído somente no mês seguinte.

