# La Onda — Relatório de Criativos (últimos 7 dias)

## Etapa 1 — Análise interna

**Estrutura da conta:** duas campanhas com objetivos diferentes:
1. `leg_tfg seguidores_euro summer` — objetivo visitas ao perfil (`profile_visit_view`)
2. `Vendas site_ Laonda` — campanha de remarketing/e-commerce com vários ad sets por estágio de funil (view content, add to cart, initiate checkout, purchase). No nível de campanha o Meta devolveu `indicator: mixed / Not available` (atribuições diferentes por ad set) — segui a regra do CLAUDE.md e somei manualmente por indicador a partir do nível `ad`.

**Validações:**
- Investimento: leg_tfg (R$49,35) + Vendas site (R$232,46) = R$281,81, bate com a soma dos ads individuais.
- Resultados por indicador (somados manualmente no nível ad):
  - profile_visit_view: 391 visitas (268+113+10, confirmado também no breakdown por posicionamento: 2+41+1+109+238=391) ✅
  - offsite_conversion.fb_pixel_view_content: 15 (8+6+1)
  - offsite_conversion.fb_pixel_add_to_cart: 1
  - offsite_conversion.fb_pixel_initiate_checkout: Dado não disponível (nenhum ad reportou valor numérico)
  - offsite_conversion.fb_pixel_purchase: 1 (R$4,94)
- CTR: 751 cliques ÷ 28.428 impressões = 2,64%, coerente com a média ponderada dos ads.

**Atenção — volume insuficiente na campanha de compras:** só 1 purchase atribuída no período. Leitura direcional, não definitiva.

**Melhor criativo por objetivo:**
- Visitas ao perfil: "ad 3 visitas ao perfil" — R$31,14, 268 visitas, R$0,12/visita (claramente o mais eficiente e o de maior volume).
- Compras: "Ad 1 compra" — único ad com purchase atribuída no período, R$4,94, R$4,94/compra.

**Funil de remarketing:** a campanha "Vendas site_ Laonda" tem ad sets segmentados por estágio (quem viu a página, quem adicionou ao carrinho, quem iniciou checkout) rodando com pouquíssima verba individual (a maioria abaixo de R$1,00 e vários ad sets pausados). Isso é típico de estrutura de remarketing, mas vale revisar se esses ad sets pausados ainda fazem sentido ou se a verba deveria ser concentrada nos criativos "com edição" e carrossel que estão ativos.

---

## Etapa 2 — Relatório do cliente

*Oi pessoal, analisei os dados dos criativos da conta nos últimos 7 dias. Segue o resumo:*
*Período* : 18/08 a 24/08
*Investimento total* : R$ 281,81
*Impressões* : 28.428
*Cliques* : 751
*CTR médio* : 2,64%
Melhor criativo
*Visitas ao perfil:* ad 3 visitas ao perfil
*Campanha de compras:* Ad 1 compra
Na campanha de visitas ao perfil nós geramos 391 visitas ao perfil, com destaque para o Instagram Stories, que sozinho trouxe 238 delas.
Já na campanha de compras, tivemos 1 venda registrada via pixel no período (volume baixo essa semana, mas a estrutura de remarketing — visualização de página, carrinho, checkout — está ativa e seguimos acompanhando).
Observações:
A campanha de visitas ao perfil está bem eficiente, a R$ 0,12 por visita. Já a campanha de vendas ainda tem volume baixo para uma leitura definitiva — vamos acompanhar de perto na próxima semana e avaliar se vale concentrar mais verba nos criativos com edição e carrossel, que são os que estão ativos hoje.
Qualquer dúvida, tô à disposição.
