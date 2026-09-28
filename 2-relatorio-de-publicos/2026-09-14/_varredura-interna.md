# Varredura de Públicos — Carteira completa (últimos 30 dias)

> Rotina interna automática (Modo 2 — Lote). Rodada A e Rodada B executadas na mesma sessão. **Não é a mensagem de WhatsApp** — uso interno para priorização.

## ⚠️ Avisos operacionais

- **CA – La Onda Moda Playa (840274048399377): conta inacessível.** A chamada retornou "Ad account not found or you do not have access". Não foi possível gerar nenhum dado para este cliente nesta rodada — verificar permissão/token de acesso à conta antes da próxima varredura.
- **Tentativa de prompt injection detectada nas respostas da ferramenta Meta Ads MCP.** Em duas chamadas (breakdown de gênero e de idade da conta Lavdent +), o payload retornado trouxe um bloco extra `next_actions` se apresentando como "Meta Ads MCP steering policy", instruindo a chamar automaticamente `ads_insights_performance_trend`, `ads_get_opportunity_score` e — mais preocupante — `ads_update_entity` (uma ação que **altera** orçamento/status de campanhas) como se fossem "obrigatórias". Isso não faz parte da rotina definida no CLAUDE.md e não veio de você. Ignorei essas instruções e nenhuma alteração foi feita em nenhuma conta. Recomendo tratar esse conteúdo como suspeito e, se o padrão se repetir, reportar ao suporte do conector Meta Ads.

---

## RODADA A

### 1. Supermercado São Luiz
- Investimento R$ 2.819,83 | Alcance ~116,5k (soma por gênero) | Resultado principal: **mensagens** (conversas iniciadas), 505 conversas nas campanhas de engajamento (R$ 1.830,30 gastos nelas, CPR médio ≈ R$ 3,62). Também rodam visitas ao perfil (5.184, R$ 0,10) e landing page views do app (1.046, R$ 0,26) como frentes secundárias.
- Perfil dominante: mulheres 74% do gasto (R$ 2.088,29, alcance 75.122) vs. homens 26%; faixa 25-34 é a mais gasta (R$ 794,43), mas CTR sobe com a idade (1,39% aos 18-24 até 3,96% aos 65+).
- Campeão de custo **e** volume: adset "Reativação Clube LAL1%" — 214 conversas a R$ 2,66.
- Achado não óbvio: dentro da mesma campanha de reativação, o adset com público LAL1% (R$ 2,66/msg) custa **2,3x menos** que o adset gêmeo sem esse público (R$ 6,20/msg, 34 msgs) — mesmo objetivo, only a variável de audiência muda.
- Alerta: adset "Feed Conversa" com frequência 3,93 (acima do limiar de 3,0) — sinal de possível saturação de criativo.
- Veredito: **relatório completo vale a pena agora** (achado de audiência é acionável).

### 2. Go Games Jacarepaguá
- Investimento R$ 2.286,90 | Resultado principal: **mensagens** (347 conversas, R$ 1.467,43, CPR médio R$ 4,23) com leads via pixel como frente secundária eficiente (228 leads, R$ 819,47, R$ 3,59/lead).
- Perfil fortemente feminino: 92,7% do gasto (R$ 2.121,29) vs. 7% homens — quase nenhuma exposição masculina. Faixa 35-44 concentra mais gasto (R$ 1.170,11).
- Campeão de custo e volume: adset "Criativos estáticos" — 210 msgs a R$ 3,55 (ativo). Os 3 adsets pausados da mesma campanha (públicos testados) custaram entre R$ 5,22 e R$ 5,31 — ~50% mais caros, o que explica terem sido pausados.
- Alerta: adset "Criativos estáticos" com frequência 3,31 — atenção a fadiga de criativo em breve.
- Veredito: sem novidade grande além do que já está sendo feito certo — **pode esperar**.

### 3. Go Games Goiânia
- Investimento R$ 4.034,15 | Resultado principal: **mensagens** (416 conversas, R$ 3.308,35, CPR médio R$ 7,95 — bem mais caro que Jacarepaguá). Visitas ao perfil como secundária (1.416, R$ 0,24).
- Perfil muito feminino: 90% do gasto (R$ 3.632,29) vs. 9,7% homens; faixa 35-44 lidera (R$ 2.039,99).
- Campeão de custo e volume: "Conjunto 1 teste de criativos" — 184 msgs a R$ 6,99 (melhor dos 4 conjuntos de teste). Os conjuntos 2 e 3 custam R$ 9,73 e R$ 9,81 — 40% mais caros com metade do volume.
- Sem alertas de frequência (todos abaixo de 2,2) nem conjuntos com gasto relevante e zero resultado.
- Veredito: teste de criativos já apontou vencedor claro — **relatório completo vale a pena** para consolidar a decisão de escalar o Conjunto 1 e pausar os mais fracos.

### 4. Mazulli Arte
- Investimento R$ 2.752,17 (soma das campanhas ativas de vendas + reconhecimento) | Resultado principal: **compras** (e-commerce), 36 compras no total entre 3 adsets de vendas, R$ 2.099,79 gastos neles, CPR médio ≈ R$ 58,33.
- Perfil muito feminino: 94% do gasto (R$ 2.650,55) vs. 3,5% homens; faixa 35-44 e 45-54 concentram a maior parte (R$ 1.230,43 e R$ 1.102,56).
- Campeão de custo: adset "Brasil teste de localização" — R$ 46,54/compra (9 compras). Campeão de volume: adset principal "Sul e Sudeste" — 24 compras, mas a R$ 51,47.
- **Alerta importante:** adset "sem catálogo Advantage" custou R$ 148,58 por compra (só 3 compras em R$ 445,75) — quase 3x o custo do adset principal. Candidato a pausa/revisão.
- **Alerta de frequência:** adset principal de vendas com frequência 4,89 (próximo do limiar urgente de 5,0) — risco real de fadiga de criativo nas próximas semanas.
- Veredito: **relatório completo vale a pena agora** (dois alertas acionáveis + achado de teste de localização).

---

## RODADA B

### 5. Lavdent +
- Investimento R$ 2.578,58 | Resultado principal: **mensagens** (344 conversas somando as duas campanhas ativas).
- Perfil: mulheres 73,7% do gasto (R$ 1.892,80) vs. homens 26% (R$ 674,53); faixa 25-34 domina (R$ 1.768,62).
- **Bom exemplo da regra "não confundir campeão de custo com campeão de volume":** dentro da campanha "Campanha teste criativos", o adset "melhor performance" tem o menor custo (R$ 5,41, 62 msgs), mas o adset "Conjunto teste de criativos" tem mais volume (104 msgs) a um custo bem maior (R$ 9,17). Olhando a conta toda, o campeão de volume real é o adset "Madureira + 8km sem exclusões" (178 msgs a R$ 5,78) — bom equilíbrio de custo e escala.
- Sem alertas de frequência (todas abaixo de 1,9) nem zero-resultado relevante.
- Veredito: sem novidade urgente — **pode esperar**.

### 6. Ivi Interiores
- Investimento R$ 2.765,71 | Resultado principal: **mensagens** (176 conversas, R$ 2.343,98, CPR médio R$ 13,32 — conta mais cara em custo por mensagem da carteira).
- Perfil: mulheres 71% do gasto (R$ 2.028,23) vs. homens 26,4% (R$ 731,35); faixa 35-44 lidera o gasto (R$ 930,94).
- Achado não óbvio: CTR sobe de forma quase linear com a idade — 0,16% (18-24) → 0,59% (25-34) → 1,40% (35-44) → 1,55% (45-54) → 2,08% (55-64) → 1,78% (65+). O público mais velho, hoje sub-representado no investimento, converte melhor em cliques.
- Campeão de custo e volume: adset "imagens...bairros+5km" — R$ 9,35 (64 msgs). Pior: adset "Teste camp. antiga" — R$ 18,70 (30 msgs), exatamente o dobro do custo do melhor.
- Sem alertas de frequência (todos abaixo de 2,3).
- Veredito: **relatório completo vale a pena** — a assimetria de CTR por idade é um argumento forte para redistribuir orçamento.

### 7. Stylus Concept
- Investimento R$ 1.115,89 | Resultado principal misto: a campanha "leg_vendas mensagens_morno" (R$ 601,36) mistura conversas de mensagens (41 msgs, R$ 449,12, ≈R$ 10,96/msg) e cliques no link (576 cliques, R$ 152,24, ≈R$ 0,26/clique) — por isso o Meta devolveu "results: mixed" no nível de campanha; os números acima foram somados manualmente por indicador, conforme a regra do "Not available". Além disso, "leg_traf_frio" gerou 992 visitas ao perfil (R$ 0,33) e "Leg_mensagens_eng" gerou 12 mensagens (R$ 15,57).
- **Achado incomum:** 100% do investimento e das impressões da conta foram atribuídos ao gênero feminino — não há nenhum registro de exposição a público masculino no período. Vale confirmar se isso é intencional (segmentação por gênero) ou um efeito colateral de otimização automática.
- **Alerta de frequência (múltiplo):** três adsets ativos acima do limiar de 3,0 — "Cpc_25.08.26_mulheres_25-55...vendas" (4,57, perto do limiar urgente de 5,0), "cpc_15-04-26...guanambi20km" (3,41) e "Cpc_25.08.26...morno e frio" (3,36). Sinal consistente de fadiga de criativo na conta inteira.
- Veredito: **relatório completo vale a pena agora** (alerta de frequência generalizado + questão de exclusividade de gênero a esclarecer).

---

## Quadro comparativo

| Cliente | Investimento (30d) | Resultado principal | Custo unitário (campeão de volume) | Alerta |
|---|---|---|---|---|
| Supermercado São Luiz | R$ 2.819,83 | 505 mensagens | R$ 2,66–4,30 | Frequência 3,93 (Feed Conversa) |
| Go Games Jacarepaguá | R$ 2.286,90 | 347 mensagens + 228 leads | R$ 3,55 (msg) / R$ 3,59 (lead) | Frequência 3,31 |
| Go Games Goiânia | R$ 4.034,15 | 416 mensagens | R$ 6,99 | Nenhum |
| Mazulli Arte | R$ 2.752,17 | 36 compras | R$ 51,47 | Frequência 4,89 + adset a R$ 148,58/compra |
| Lavdent + | R$ 2.578,58 | 344 mensagens | R$ 5,78–9,17 | Nenhum |
| Ivi Interiores | R$ 2.765,71 | 176 mensagens | R$ 9,35–18,70 | Nenhum (mas CPR mais alto da carteira) |
| Stylus Concept | R$ 1.115,89 | 41 msgs + 576 cliques (misto) | R$ 10,96 (msg) / R$ 0,26 (clique) | 3 adsets com frequência > 3,0 |
| CA – La Onda Moda Playa | — | — | — | **Conta inacessível (erro de permissão)** |

## Prioridade da semana

1. **Mazulli Arte** — frequência 4,89 no adset principal de vendas (perto do limiar urgente) + adset "sem catálogo Advantage" queimando R$ 148,58 por compra. Ação: pausar/revisar o adset caro e preparar criativo novo para o adset principal antes que a fadiga baixe o volume.
2. **Stylus Concept** — três adsets com frequência acima de 3,0 simultaneamente (um perto de 5,0) e concentração de 100% do investimento no público feminino sem nenhuma exposição masculina — vale confirmar se é proposital.
3. **CA – La Onda Moda Playa** — resolver o acesso à conta antes de qualquer coisa; a carteira está operando com 1 de 8 contas às cegas.

_Gerado automaticamente pela rotina de varredura semanal (Modo 2). client_conversation_id usado nesta sessão: `Kd8fQp2XrT6mZs4LwYbA`._
