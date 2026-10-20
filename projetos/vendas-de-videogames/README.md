# Vendas de videogames

## Contexto e objetivo
Uma loja precisa planejar campanhas e catálogo para 2017. O projeto compara vendas de 2013 a 2016 por plataforma, gênero e região e verifica diferenças nas avaliações dos usuários.

## Ferramentas
Python, pandas, matplotlib, seaborn e SciPy.

## Etapas
Preparação de tipos e valores ausentes; análise temporal por plataforma; vendas totais e medianas por gênero; perfis regionais e classificações etárias; testes de hipóteses sobre avaliações.

## Resultados encontrados
- PS4 somou 314,14 milhões de unidades no período; Xbox One, 159,32 milhões.
- Action liderou em vendas totais (321,87 milhões), mas teve mediana de 0,11 milhão por título. Shooter somou 232,98 milhões e teve a maior mediana (0,45 milhão).
- Avaliações de Xbox One e PC não mostraram diferença estatística (p ≈ 0,148). Action e Sports diferiram (médias 6,84 e 5,24; p ≈ 1,45 × 10⁻²⁰; α = 0,05).

## Conclusões e recomendações
O notebook prioriza PS4 e, depois, Xbox One para o planejamento de 2017 e destaca Shooter pela mediana de vendas por jogo. O volume total de Action também reflete a quantidade de títulos. As recomendações se limitam ao recorte histórico analisado.

## Arquivos e reprodução
Notebook: [`analise-vendas-videogames.ipynb`](analise-vendas-videogames.ipynb). Dependências: [`requirements.txt`](requirements.txt). O notebook requer `games.csv`, não incluído por falta de confirmação de licença. Obtenha uma cópia autorizada, coloque-a ao lado do notebook e execute com esta pasta como diretório de trabalho; o `.gitignore` impede seu versionamento.