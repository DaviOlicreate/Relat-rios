# Stylus Concept — Relatório de Públicos — 28/08/2026 (últimos 30 dias)

## PARTE 1 — Mensagem para o cliente

Oii, pessoal! Tudo bem? Segue nosso relatório de públicos dos últimos 30 dias:

📊 Visão Geral
━━━━━━━━━━━━━
- Investimento total: R$ 1.426,50. Frente principal: mensagens no WhatsApp (R$ 578,96, 174 mensagens, R$ 3,33 por mensagem). Frente de apoio: visitas ao perfil (R$ 501,94, 2.000 visitas, R$ 0,25 por visita).

👥 Perfil Demográfico
━━━━━━━━━━━━━
- Toda a frente de mensagens está direcionada ao público feminino (100% do investimento rastreado, R$ 578,96) — a segmentação já foi configurada só para mulheres.
- Na frente de visitas ao perfil, mulheres também concentram praticamente 100% do investimento (R$ 501,94) — a conta como um todo está voltada para esse público.

Faixa Etária Principal
━━━━━━━━━━━━━
- Na frente de mensagens, a faixa de 35 a 44 anos é a mais forte: R$ 277,64 (48% do investimento dessa frente), 91 mensagens e o melhor custo, R$ 3,05 cada.
- Na frente de visitas ao perfil, a faixa de 25 a 34 anos se destaca: R$ 172,12 (34%), 831 visitas a R$ 0,21 cada — a mais barata entre todas as faixas.

📱 Plataformas
━━━━━━━━━━━━━
- O Instagram domina as duas frentes: 95% do investimento em mensagens (R$ 552,28, R$ 3,35 por mensagem) e 89% em visitas ao perfil (R$ 445,50, R$ 0,25 por visita).
- O Facebook tem volume pequeno nas duas frentes, mas custo por resultado um pouco melhor (R$ 2,96 por mensagem e R$ 0,28 por visita) — leitura direcional dado o volume baixo.

🎯 Performance de Segmentação (quais públicos trazem o melhor custo)
━━━━━━━━━━━━━
- Campeão de custo e de volume em mensagens: o conjunto ativo "mulheres 25-55, Guanambi e Tanque Novo" trouxe 165 das 174 mensagens a R$ 3,00 cada.
- Ponto de atenção: esse mesmo conjunto está com frequência de 5,24 em 30 dias — acima do limite de alerta (5,0). O público já viu o anúncio mais de 5 vezes, em média, e o custo por mensagem tende a subir se o criativo não for renovado.
- O conjunto de visitas ao perfil também está no limite: frequência de 4,97, quase no mesmo alerta.
- O conjunto irmão de mensagens (já pausado) custava R$ 9,37 por mensagem — mais que o triplo do conjunto ativo. Bom que já foi pausado.

✅ Plano de Ação
1. Renovar os criativos (ou ampliar o público) dos dois conjuntos principais — ambos estão no limite de frequência (4,97 e 5,24) e o custo deve subir se não houver ação.
2. Escalar levemente a faixa de 25-34 anos na frente de visitas ao perfil, que tem o melhor custo.
3. Considerar testar públicos além do feminino, já que hoje praticamente toda a verba rastreada por gênero está indo para mulheres.
4. Confirmar se há rastreamento de vendas (pixel/catálogo) configurado — vale alinhar esse ponto internamente para o próximo ciclo.

Qualquer dúvida, é só chamar!

## PARTE 2 — Notas internas (não enviar ao cliente)

- A campanha principal se chama "leg_vendas mensagens_morno" mas nenhum conjunto está otimizado para compras (omni_purchase nulo em todos) — o resultado real que ela gera é mensagem (CONVERSATIONS) e clique no link (LINK_CLICKS). Vale confirmar com o cliente se há pixel/catálogo configurado ou se a venda acontece manualmente após a conversa no WhatsApp; nesse segundo caso, sugiro renomear a campanha para refletir o objetivo real e evitar confusão de leitura.
- Dois conjuntos-chave (mensagens ativo e visitas ao perfil) estão com frequência entre 4,97 e 5,24 — ambos no limite ou acima do alerta urgente de saturação (5,0). Recomendo trocar criativo ou ampliar público no próximo ciclo antes que o custo suba mais.
- Toda a segmentação de gênero rastreada está praticamente 100% em mulheres — não há teste de público masculino rodando atualmente; pode ser proposital (perfil de cliente da loja) ou uma oportunidade ainda não testada.
- O campo "results" veio "mixed" tanto no nível conta quanto no nível da campanha "leg_vendas mensagens_morno", porque ela mistura conjuntos otimizados para mensagens e para cliques no link — a validação teve que ser refeita no nível do conjunto de anúncios (adset), separando por optimization_goal.

## Validações rodadas
- Soma de investimento por breakdown (gênero, idade, plataforma) da frente de mensagens = R$ 578,96 em todos os casos; da frente de visitas ao perfil = R$ 501,94 em todos os casos. ✓
- Soma de resultados por breakdown: mensagens 165+9=174 (bate com o total); visitas 1985+15=2000 (bate com o total). ✓
- Coerência de custo: 494,65/165 = R$ 3,00; 172,12/831 = R$ 0,21 — batem com o cost_per_result do Meta. ✓
- Coerência de CTR verificada nos breakdowns. ✓
