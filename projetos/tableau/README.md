# Dashboard de tendências do YouTube

## Contexto e objetivo
O dashboard reúne tendências de vídeos por data, categoria e país para comparar volume e composição das categorias entre regiões.

## Ferramenta e arquivos
Tableau. Os arquivos deste projeto estão incluídos no repositório:

- [`tableau-dashboard.twbx`](tableau-dashboard.twbx): workbook empacotado, com quatro planilhas e o dashboard `Painel 1`.
- [`relatorio-tableau.pdf`](relatorio-tableau.pdf): apresentação de sete páginas com perguntas e conclusões associadas.

O workbook contém abas chamadas `Histórico percentual`, `Tabela de destaque`, `Valor absoluto` e `Vídeos por país`. O pacote inclui um extrato `.hyper`, mas também guarda uma referência ao caminho local `C:/Users/Laptop/Downloads/trending_by_time.csv`. Para atualizar os dados em outro computador, pode ser necessário reconectar essa fonte no Tableau. A integridade do pacote foi verificada como arquivo ZIP; não foi possível abrir o workbook no aplicativo Tableau nesta revisão.

[Abrir o dashboard no Tableau Public](https://public.tableau.com/views/Projeto-Sprint12-Automao/Painel1?:language=pt-BR&:publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) — link encontrado nos arquivos; o acesso atual não pôde ser confirmado.

## Perguntas de negócio
- Quais categorias aparecem em alta com maior frequência?
- Como o volume de vídeos em alta se distribui entre países?
- Quais categorias se destacam nos Estados Unidos em comparação com outros países?

## Principais insights registrados
Segundo o PDF, Entertainment teve o maior volume nos Estados Unidos (19.638), seguida por Music (12.874) e Howto & Style (8.280). Os Estados Unidos lideraram o volume entre países; o Japão teve volume consideravelmente menor. Entertainment também se destacou nos Estados Unidos, com 32.924 registros no recorte descrito.

Os valores foram transcritos da apresentação existente. Os arquivos não identificam suficientemente a fonte, o período ou a metodologia; leia-os como resultados do dashboard, não como estatísticas atuais da plataforma.

## Conclusão
A apresentação recomenda acompanhar categorias frequentes e comparar o mix por país. Recomendações operacionais dependem da confirmação da fonte e do período dos dados.

## Compartilhamento e reprodução
Este projeto não usa Python. O dashboard online também pode ser consultado pelo link do Tableau Public acima, cuja disponibilidade atual não foi confirmada.
