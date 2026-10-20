# Sazonalidade hoteleira

## Contexto e objetivo
Variações de demanda ao longo do ano afetam preços, equipes e planejamento. O projeto compara City Hotel e Resort Hotel, observa o ADR (tarifa média diária) e testa padrões mensais nas reservas.

## Ferramentas
Python, pandas, matplotlib e SciPy.

## Etapas
Inspeção de 119.390 registros e 36 colunas; remoção de `name`, `email`, `phone-number` e `credit_card`; tratamento de valores ausentes; análise mensal de demanda e ADR; teste t de Welch para ADR em períodos de alta e baixa demanda e qui-quadrado para mês de chegada versus tipo de hotel.

## Resultados encontrados
- Agosto teve mais reservas (13.877) e janeiro, menos (5.929). City Hotel superou Resort Hotel em todos os meses; ambos atingiram o pico em agosto.
- Alta demanda reúne março, abril, maio, agosto, setembro e outubro, definidos pela mediana mensal de 3.217 reservas.
- ADR médio: 104,47 na alta e 94,23 na baixa; teste t de Welch p ≈ 1,38 × 10⁻¹⁷⁸.
- Associação entre mês e tipo de hotel: χ² = 598,13, 11 graus de liberdade, p ≈ 3,52 × 10⁻¹²¹.

## Conclusões e recomendações
Os resultados apoiam padrões sazonais e diferenças mensais entre os tipos de hotel, úteis para orientar análises de capacidade e preço. Não demonstram causalidade. O notebook registra ADRs negativos e valores extremos, que limitam a interpretação e precisam de validação antes de decisões de preço.

## Segurança e reprodução
Notebook: [`sazonalidade-hoteleira.ipynb`](sazonalidade-hoteleira.ipynb). Dependências: [`requirements.txt`](requirements.txt). O notebook requer `hotel_booking.csv`, que não foi copiado: a base contém nomes, e-mails, telefones e cartões mascarados, e a permissão de compartilhamento não está confirmada. Não publique o CSV original. Use somente uma versão autorizada e sem identificadores, revisando dados e saídas antes de compartilhar.