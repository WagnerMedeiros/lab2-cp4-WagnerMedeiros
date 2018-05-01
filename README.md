O relat�rio para esta atividade poder� ser encontrado no link abaixo:

http://rpubs.com/WagnerSantos/wikimediafondation

## Sess�es, buscas e navega��o na wikimedia

Este repo � a semente para uma an�lise de padr�es de busca e navega��o em p�ginas de projetos da wikimedia (provavelmente wikipedia).

O exerc�cio original de an�lise � um problema proposto pela Wikimedia "for candidates applying to be a Data Analyst in the Discovery department at Wikimedia Foundation." O README do projeto original descreve as an�lises pedidas aos interessados na posi��o.

## Organiza��o

code: c�digo para importar + transformar dados para an�lise, c�digo de fun��es �teis em mais de um ponto.

data: dados criados para essa an�lise.

reports: notebooks das an�lises.

## O que j� temos

Como as an�lises propostas na tarefa original s�o em sua maioria sobre resultados de buscas e a navega��o que acontece depois delas, j� h� c�digo para ler os dados originais e criar algumas m�tricas sobre buscas nas sess�es de usu�rio e sobre a navega�ao depois de cada busca em code/import-events_to_searches.R. Executar Rscript code/import-events_to_searches.R gera o arquivo data/search_data.csv. O script import-events_to_searches.R em si � a melhor documenta��o do que significa cada coluna em data/search_data.csv.

## Depend�ncias

R, com os pacotes tidyverse, lubridate e here.