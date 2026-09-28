# Stylus Concept — Relatório de Criativos (últimos 7 dias)

## Etapa 1 — Análise interna

**Estrutura da conta:** duas campanhas com objetivos diferentes:
1. `leg_traf_frio` — objetivo visitas ao perfil (`profile_visit_view`)
2. `leg_vendas mensagens_morno` — campanha que mistura ad sets otimizados para cliques no link (`actions:link_click`) e ad sets otimizados para mensagens (`onsite_conversion.messaging_conversation_started_7d`). No nível de campanha o Meta devolveu `indicator: mixed / Not available` — segui a regra do CLAUDE.md e somei manualmente por indicador no nível ad.

**Validações:**
- Investimento: leg_traf_frio (R$116,06) + leg_vendas mensagens_morno (R$284,79) = R$400,85, bate com a soma dos ads.
- Dentro de leg_vendas mensagens_morno: cliques no link R$115,03 + mensagens R$169,76 = R$284,79 ✅
- Resultados: visitas ao perfil = 350 (bate com o breakdown por posicionamento: 2+33+151+28+136=350). Cliques no link = 417. Mensagens = 16.
- CTR: 1.049 cliques ÷ 57.252 impressões = 1,83%, coerente com a média ponderada dos ads.

**Melhor criativo por objetivo:**
- Visitas ao perfil: "ad preço fixo" — R$74,96, 236 visitas, R$0,32/visita.
- Cliques no link: "ad5_conjunto_24-04" — R$59,06, 215 cliques, R$0,27/clique.
- Mensagens: "ad preço fixo" — R$36,11, 7 mensagens, R$5,16/mensagem (melhor custo entre os ads de mensagem; uma variação do mesmo nome de criativo rodando com verba maior, R$47,65, ficou em R$11,91/mensagem — mais que o dobro do custo).

**Atenção:** vários dos ad sets mais eficientes (o de cliques "ad5_conjunto_24-04" e o de mensagens mais barato) já estão com status ADSET_PAUSED/PAUSED. Vale confirmar se a pausa foi intencional (fim de promoção, esgotou estoque) ou se deveriam voltar ativos, já que tiveram os melhores custos da conta.

---

## Etapa 2 — Relatório do cliente

*Oi pessoal, analisei os dados dos criativos da conta nos últimos 7 dias. Segue o resumo:*
*Período* : 18/08 a 24/08
*Investimento total* : R$ 400,85
*Impressões* : 57.252
*Cliques* : 1.049
*CTR médio* : 1,83%
Melhor criativo
*Visitas ao perfil:* ad preço fixo
*Cliques no link:* ad5_conjunto_24-04
*Mensagens:* ad preço fixo
Na campanha de tráfego geramos 350 visitas ao perfil no período. Nos conjuntos otimizados para cliques no link tivemos 417 cliques, e nos conjuntos de mensagens conseguimos 16 mensagens iniciadas.
Observações:
O criativo "ad preço fixo" está funcionando bem tanto para visitas quanto para mensagens, mas notamos que a versão dele com mensagens mais baratas (R$ 5,16 por mensagem) está pausada, enquanto uma variação mais cara (R$ 11,91 por mensagem) seguiu ativa. Vale a gente confirmar se dá pra reativar a versão mais barata para melhorar o custo médio da campanha de mensagens.
Qualquer dúvida, tô à disposição.
