# Mazulli Arte — relatório avulso (formato da rotina)

Janela atual: 20/11 a 26/11 (7 dias). Comparação: 13/11 a 19/11 (7 dias). Fonte: Meta Ads (MCP), nível campanha, dados puxados em 27/11/2026.

## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Olá pessoal! Tudo bem?

Pessoal, estou enviando aqui o relatório dos últimos 7 dias de campanhas (20/11 a 26/11):

---

✅ *Resumo:*

* *Valor TOTAL investido:* R$ 628,23 (+6,4% que a semana anterior)
* *Impressões/Visualizações:* 39.936 (+15,0% que a semana anterior)
* *CPM (Custo para cada 1mil visualizações):* R$ 15,73 (-7,4% que a semana anterior)
* *Cliques:* 1.953 (+10,7% que a semana anterior)
* *CTR (Taxa de Cliques):* 4,89% (-3,7% que a semana anterior)
* *Número de compras:* 18 (-10,0% que a semana anterior)
* *Média de compras por dia:* 2,57
* *Custo por compra:* R$ 34,90 (+18,3% que a semana anterior)
* *Faturamento:* R$ 2.354,72 (-7,7% que a semana anterior)
* *ROAS:* 3,75 (-13,2% que a semana anterior)

💡 Comentários:

Investimos R$ 628,23 esta semana e geramos 18 compras, com custo médio de R$ 34,90 cada. As vendas recuaram um pouco em relação à semana anterior, mas a loja apareceu para mais gente pagando menos (CPM 7,4% menor, 15% mais impressões) e cada real investido voltou como R$ 3,75 em vendas; o ajuste agora é concentrar a verba nas campanhas que estão vendendo mais barato para aproveitar a Black Friday.

Vamos continuar monitorando a qualidade e ajustando as campanhas para melhorar a performance, sempre com o objetivo de escalar os resultados.

Gostaria de saber de vocês qual foi a percepção referente ao desempenho na semana e nas últimas mudanças.
```

## ANÁLISE INTERNA (não enviar)

### Composição

| Campanha | Indicador | Atual (20/11–26/11) | Anterior (13/11–19/11) |
|---|---|---|---|
| leg_mazulli_vendas ROAS | Compras | 7 · R$ 272,29 · **R$ 38,90** · fat. R$ 1.039,11 (ROAS 3,82) | 11 · R$ 270,55 · R$ 24,60 · fat. R$ 1.691,83 (ROAS 6,25) |
| leg_conv_frio_backup | Compras | 6 · R$ 164,44 · R$ 27,41 · fat. R$ 922,52 (ROAS 5,61) | 6 · R$ 131,65 · R$ 21,94 · fat. R$ 690,41 (ROAS 5,24) |
| [vendas]_advantag_catálogo | Compras | 5 · R$ 149,88 · R$ 29,98 · fat. R$ 393,09 (ROAS 2,62) | 3 · R$ 147,49 · R$ 49,16 · fat. R$ 167,98 (ROAS 1,14) |
| leg_seguidores_mazulli | **Visitas ao perfil** (não é compra) | 167 · R$ 41,62 · R$ 0,25 | 203 · R$ 40,57 · R$ 0,20 |

- Custo por compra com verba total: R$ 34,90 contra R$ 29,51 (+18,3%). **Versão limpa** (só vendas, R$ 586,61 contra R$ 549,69): **R$ 32,59 contra R$ 27,48 (+18,6%)**. ROAS limpo: 4,01 contra 4,64.
- Ticket médio: R$ 130,82 contra R$ 127,51 (estável).

### Leitura
- **Fato:** a queda veio toda da vendas ROAS (11 → 7 compras com a mesma verba; ROAS 6,25 → 3,82). CTR dela caiu (4,55% → 4,21%).
- **Fato:** o catálogo melhorou bastante (R$ 49,16 → R$ 29,98; ROAS 1,14 → 2,62) e a frio_backup segue a de melhor ROAS (5,61), com +25% de verba.
- **Hipótese:** pré-Black Friday — compradores adiando a compra para 27/11, o que tende a afetar mais a campanha de público quente/ROAS.
- Volume pequeno (18 contra 20, diferença de 10%): leitura direcional.
- **Ação:** durante a BF, reforçar a frio_backup; acompanhar a vendas ROAS diariamente antes de cortar.
- leg_seguidores: visitas -17,7%, custo R$ 0,20 → R$ 0,25.

### Notas técnicas
- Investimento +6,4% (dentro do limite).
- Atribuição diferente entre campanhas de vendas (vendas ROAS: 1d_view_7d_click; catálogo e frio_backup: 1d_view_7d_click_1d_ev). O indicador de resultado veio como `offsite_conversion.fb_pixel_purchase` e bate com `omni_purchase` em todas.
- Validações: custo por resultado do Meta = investimento ÷ compras; cliques ÷ impressões = CTR reportado. CPM e CTR da conta recalculados a partir dos totais.
