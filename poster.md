# Questões de Investigação

## Descrição do Dataset
O projeto visa construir uma solução de data analytics sobre avistamentos de cogumelos na Península Ibérica, cruzando dados de localização, espécie e sazonalidade com informação de toxicidade obtida de fontes externas (ex: bases de dados micológicas). O objetivo é apoiar a sensibilização da população para os riscos de ingestão de cogumelos selvagens.

## DW - Data Warehouse (Descriptive/Diagnostic)

- Quais as espécies de cogumelos mais avistadas por região e por estação do ano?
	- Análise de frequência por espécie, região e estação.

- Existem regiões e épocas do ano com maior concentração de espécies perigosas, considerando apenas avistamentos verificados pela comunidade científica?
	- Análise de concentração de espécies perigosas por região e estação, filtrando por avistamentos verificados.

- Em que regiões e para que espécies a população tem mais dificuldade em identificar corretamente os cogumelos que encontra?
	- Análise de erros de identificação por região e espécie, usando dados de avistamentos com identificação incorreta.

## DM - Data Mining (Predictive/Prescriptive)

- Com base na localização e época do ano, qual o risco esperado (venenoso/comestível) de um cogumelo avistado nessa zona?
	- Modelo de classificação para prever a toxicidade com base em localização e estação.

- Consegue-se prever em que situações é mais provável que uma pessoa identifique erradamente um cogumelo, potencialmente confundindo uma espécie perigosa com uma comestível?
	- Modelo de classificação para prever erros de identificação com base em região, estação e espécie.

- Que combinações de região e época do ano estão mais frequentemente associadas ao aparecimento de espécies perigosas específicas?
	- Análise de associação para identificar combinações de região e estação associadas a espécies perigosas específicas.

## Star Model

Ficheiro json, carregar no onda e finalizar