# Lavdent + — Relatório de Públicos — 28/08/2026 (últimos 30 dias)

## PARTE 1 — Mensagem para o cliente

Oii, pessoal! Tudo bem? Segue nosso relatório de públicos dos últimos 30 dias:

📊 Visão Geral
━━━━━━━━━━━━━
- Investimento total: R$ 2.620,19, alcançando 92.407 pessoas e gerando 383 mensagens iniciadas no WhatsApp, a um custo médio de R$ 6,84 por mensagem.

👥 Perfil Demográfico
━━━━━━━━━━━━━
- O público feminino concentra 69,6% do investimento (R$ 1.824,29) e 264 mensagens, a um custo de R$ 6,91 por mensagem.
- O público masculino recebeu 30,1% (R$ 788,80) e gerou 117 mensagens a R$ 6,74 cada — praticamente equivalente ao feminino em eficiência (diferença de só 2,5%).
- Leitura: não há motivo para migrar peso entre gêneros agora — os dois convertem de forma parecida; o volume maior de mulheres reflete o alcance da campanha, não uma vantagem real de custo.

Faixa Etária Principal
━━━━━━━━━━━━━
- A faixa de 25 a 34 anos é o núcleo: 66% do investimento (R$ 1.728,13) e 275 mensagens (72% do total), com o melhor custo entre as faixas de maior volume: R$ 6,28 por mensagem.
- A faixa de 35 a 44 anos recebeu R$ 359,72 mas saiu a R$ 10,90 por mensagem — 74% mais cara que a faixa principal, sinal de que não é o público ideal para essa oferta.
- As faixas de 45 a 65+ anos têm volume pequeno (menos de 20 mensagens cada) mas custo competitivo — leitura direcional, vale testar mais verba aqui aos poucos.

📱 Plataformas
━━━━━━━━━━━━━
- O Instagram trouxe 217 mensagens com investimento de R$ 1.247,31 (47,6%), a R$ 5,75 por mensagem.
- O Facebook recebeu mais verba (R$ 1.372,88, 52,4%) mas rendeu menos: 166 mensagens a R$ 8,27 cada — 44% mais caro que o Instagram.
- Recomendação: migrar parte da verba do Facebook para o Instagram, que converte mensagens de forma bem mais barata.

🎯 Performance de Segmentação (quais públicos trazem o melhor custo)
━━━━━━━━━━━━━
- Campeão de custo e de volume: o conjunto "Madureira + 8km sem exclusões, 24-35 anos" trouxe 180 mensagens a R$ 4,66 cada — o melhor resultado da conta em volume e custo ao mesmo tempo.
- Achado do mês: esse mesmo público rodou em duas versões — sem exclusões (R$ 4,66/mensagem, 180 mensagens) e com exclusões (R$ 11,29/mensagem, 47 mensagens). Tirar as exclusões reduziu o custo em mais da metade e quase quadruplicou o volume.
- O teste de criativos em andamento já mostra um vencedor: o conjunto "melhor performance" está a R$ 4,90 por mensagem contra R$ 6,69 do conjunto original do mesmo teste.
- Pior conjunto do mês: "Madureira 5km" (campanha pausada), a R$ 11,37 por mensagem — junto com a versão "com exclusões", reforça que restringir demais o público está encarecendo o resultado.

✅ Plano de Ação
1. Remover as exclusões de público nos conjuntos que ainda as usam — o teste já mostrou ganho de mais de 50% no custo.
2. Migrar parte da verba do Facebook para o Instagram (diferença de 44% no custo por mensagem).
3. Consolidar o orçamento no criativo vencedor do teste ("melhor performance").
4. Reduzir a fatia de verba na faixa de 35-44 anos, que está saindo 74% mais cara que o núcleo de 25-34.

Qualquer dúvida, é só chamar!

## PARTE 2 — Notas internas (não enviar ao cliente)

- A conta tem mais de 20 campanhas antigas pausadas com R$ 0,00 de investimento — vale uma limpeza/arquivamento para facilitar a leitura da conta.
- Várias campanhas ativas usam "leg_" e "fake" como prefixo interno (ex.: "leg_fake_atualizações julho") — no relatório do cliente isso foi traduzido para linguagem de negócio; sugiro alinhar a convenção de nomenclatura interna para evitar confusão.
- O campo "results" no nível ad_account veio "mixed" nos breakdowns porque a conta tem campanhas de Lead Generation e Tráfego cadastradas (mesmo com R$ 0,00 gasto) junto das de mensagens — a validação teve que ser refeita no nível campanha, filtrando só as campanhas com investimento real no período.
- O conjunto "Madureira 8km sem exclusões...vendas fake" tem R$ 21,20 investidos e resultado "Not available" — está no limite do threshold de volume insuficiente (~R$ 20); monitorar no próximo ciclo antes de tirar conclusão.

## Validações rodadas
- Soma de investimento por breakdown (gênero, idade, plataforma), somando as 4 campanhas ativas no período = R$ 2.620,19 em todos os casos. ✓ bate com a soma direta das campanhas (1.368,48 + 598,48 + 545,54 + 107,69).
- Soma de mensagens por breakdown (264+117+2=383; 42+275+33+17+9+7=383; 166+217=383) bate com a soma direta das campanhas (227+101+48+7=383). ✓
- Coerência de custo: 837,93/180 = R$ 4,66; 530,55/47 = R$ 11,29 — batem com o cost_per_result do Meta. ✓
- Coerência de CTR verificada nos breakdowns de gênero e idade. ✓
- Nota técnica: "results" no nível ad_account veio "mixed" (Not available) por causa de campanhas com objetivos diferentes na conta — os breakdowns foram refeitos no nível campanha, filtrando as campanhas com gasto real, conforme a regra do CLAUDE.md.
