# Marketing e retorno

## Contexto e objetivo
A Y.Afisha investe em diferentes origens de aquisição. O projeto analisa visitas, pedidos e custos para avaliar aquisição, retenção e retorno com LTV, CAC e ROI.

## Ferramentas
Python, pandas e matplotlib.

## Etapas
Preparação das tabelas; análise de uso por dispositivo e tráfego; cálculo de coortes, LTV, CAC e ROI por origem; comparação de canais para apoiar decisões de orçamento.

## Resultados encontrados
Nos resultados salvos no notebook, as origens 1, 2, 9 e 5 superaram 100% de ROI (149,24%, 109,62%, 104,38% e 101,67%). As origens 4, 10 e 3 ficaram abaixo de 100% (92,83%, 76,43% e 38,57%). O notebook relata predominância de acessos por desktop.

## Conclusões e recomendações
A recomendação registrada é revisar o orçamento, priorizando os canais acima de 100% e investigando os de menor retorno, especialmente a origem 3. As métricas dependem do período e das definições usadas no notebook; não garantem desempenho futuro.

## Arquivos e reprodução
Notebook: [`marketing-e-retorno.ipynb`](marketing-e-retorno.ipynb). Dependências: [`requirements.txt`](requirements.txt). O notebook requer `visits_log_us.csv`, `orders_log_us.csv` e `costs_us.csv`. Não foram copiados: os logs incluem identificadores de usuários e a permissão de compartilhamento não foi confirmada. Obtenha cópias autorizadas e coloque-as ao lado do notebook; o `.gitignore` impede seu versionamento.