# Mercado de táxis em Chicago

## Contexto e objetivo
A Zuber avalia como entrar no mercado de Chicago. O projeto explora a concentração entre empresas e destinos e testa se a duração média de viagens do Loop ao Aeroporto O’Hare difere em sábados chuvosos.

## Ferramentas
Python, pandas, matplotlib, seaborn e SciPy. Os arquivos disponíveis são resultados agregados de consultas SQL; as consultas originais não foram encontradas, então essa etapa não é reproduzível com os materiais atuais.

## Etapas
Leitura dos resultados sobre empresas, destinos e viagens; ordenação das empresas por número de corridas e dos destinos por média; comparação da duração entre grupos e teste estatístico.

## Resultados encontrados
Flash Cab teve 19.558 viagens, seguida por Taxi Affiliation Services, com 11.422. Loop liderou a média por destino (10.727,47), seguido por River North (9.523,67). O teste da duração em sábados chuvosos reportou p ≈ 6,74 × 10⁻¹²; com α = 0,05, o notebook rejeita a hipótese nula de médias iguais.

## Conclusões e recomendações
O notebook recomenda diferenciação frente à empresa líder e atenção a áreas movimentadas. O teste identifica diferença entre os grupos comparados, mas não demonstra que a chuva cause essa diferença.

## Arquivos e reprodução
Notebook: [`analise-taxis-chicago.ipynb`](analise-taxis-chicago.ipynb). Dependências: [`requirements.txt`](requirements.txt). O notebook requer `project_sql_result_01.csv`, `project_sql_result_04.csv` e `project_sql_result_07.csv`; não incluídos por falta de confirmação de compartilhamento. Obtenha os resultados de fonte autorizada e coloque-os ao lado do notebook. As consultas SQL originais não estão disponíveis.