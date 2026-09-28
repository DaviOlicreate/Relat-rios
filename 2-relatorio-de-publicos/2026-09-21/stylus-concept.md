# Stylus Concept — Relatório de Públicos (últimos 30 dias)

## PARTE 1 — Mensagem pronta para o cliente

Oii, [NOME DO CONTATO]! Tudo bem? Segue nosso relatório de públicos dos últimos 30 dias:

👥 Perfil Demográfico
━━━━━━━━━━━━━
- 100% do investimento (R$ 1.007,89) foi direcionado e entregue para o público feminino nesse período — não houve entrega registrada para homens
- Ainda não temos teste rodando com público masculino nesta conta
- Recomendo mantermos o foco 100% feminino por ora, já que é a única base de dados que temos pra decisão

Faixa Etária Principal
━━━━━━━━━━━━━
- A faixa de 35 a 44 anos é a principal, com 39,8% do investimento (R$ 401,36)
- A faixa de 45 a 54 anos vem em seguida, com 29,6% (R$ 297,83), e 25-34 com 26% (R$ 262,15) — as três faixas de 25 a 54 anos concentram 95,4% do investimento
- Praticamente nada foi investido em 55+ (4,6%) — sem volume suficiente pra qualquer conclusão

📱 Plataformas
━━━━━━━━━━━━━
- O Instagram concentra 85,8% do investimento (R$ 864,42), mas com CTR de apenas 1,12%
- O Facebook, mesmo recebendo só 14,2% da verba (R$ 143,47), teve um CTR mais que o dobro do Instagram: 2,53%
- Vale um teste com mais verba no Facebook pra ver se esse CTR mais alto se sustenta em volume maior

🎯 Performance de Segmentação (quais públicos trazem o melhor custo)
━━━━━━━━━━━━━
- Campeão de custo: o conjunto de mensagens "morno e frio" (mulheres 25-54, Guanambi e Tanque Novo) trouxe 24 mensagens a R$ 10,14 cada
- Campeão de volume: o conjunto de mensagens "vendas" (mulheres 25-55, mesma região) trouxe 33 mensagens, só um pouco mais caro, a R$ 10,18
- O conjunto de tráfego pro perfil ("todos 25-65, lookalike Guanambi 20km") trouxe 745 visitas a só R$ 0,37 cada — ótimo custo, mas é topo de funil, não venda
- Atenção: os dois conjuntos de mensagens acima já estão com frequência alta (4,39 e 3,71) — a audiência está saturando e o custo por mensagem tende a subir se não ampliarmos o público

Observações:
A campanha principal de vendas ("leg_vendas mensagens_morno") gastou R$ 486,06 no período — quase metade do investimento total da conta — mas o Meta não conseguiu nos dar o número de vendas geradas por ela, porque o evento de resultado dessa campanha veio como "não disponível" nas nossas conferências. Antes de continuar escalando essa campanha, vamos revisar a configuração de rastreamento (pixel/evento de compra) pra garantir que as vendas estão sendo contadas corretamente. Só depois disso conseguimos te dizer o custo por venda real.

Qualquer dúvida, tô à disposição.

---

## PARTE 2 — Notas internas (NÃO enviar ao cliente)

- **Achado técnico prioritário**: a campanha "leg_vendas mensagens_morno" (objetivo OUTCOME_SALES, R$ 486,06 gastos = 48,2% do investimento total da conta) retornou `results.indicator = "mixed"` mesmo no nível campanha. Ao consultar diretamente os campos `omni_purchase`, `offsite_conversion_fb_pixel_purchase` e `onsite_conversion_purchase`, todos vieram `null` — ou seja, zero vendas atribuídas nesta campanha nos últimos 30 dias, apesar de 567 cliques no link registrados. Isso é forte indício de pixel/evento de compra mal configurado ou catálogo desconectado, não apenas de baixo desempenho. **Prioridade: revisar o pixel/CAPI dessa conta antes do próximo relatório.**
- Saturação confirmada em dois conjuntos ativos de mensagens: frequência 4,39 (quase no limite urgente de 5,0) e 3,71. Ambos precisam de ampliação de público ou pausa em breve.
- Público 100% feminino pode ser reflexo de segmentação fechada (conferir configuração de público) ou de um comportamento real de compra — vale confirmar com o cliente antes de tratar como definitivo.
- Contato do cliente não estava preenchido na tabela da rotina — usar o nome real antes de enviar a mensagem final.

---

## Validação

- Soma de investimento (gênero, idade e plataforma) bate com o total da conta: R$ 1.007,89.
- Dado não disponível: número de vendas da campanha "leg_vendas mensagens_morno" — indicador "mixed" e campos de compra retornaram null em consulta direta.
