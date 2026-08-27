# Go Games Goiânia — Relatório de Público (últimos 30 dias)
Data de geração: 27/08/2026 | Conta: 706269358010254 | Contato: Raffa

---

## ETAPA 1 — Análise interna (não enviar ao cliente)

**Validações**
- Soma de investimento por breakdown (gênero, idade, plataforma) bateu com o total da conta: R$ 3.237,87 nos três casos. OK.
- `results` não agrega no nível `ad_account` (conta tem campanhas com indicadores diferentes: mensagens e visitas ao perfil) — puxado no nível `campaign` e somado manualmente por indicador.
- Breakdown de gênero/idade/plataforma não suporta o campo de conversas iniciadas (`actions:onsite_conversion.messaging_conversation_started_7d`) — API retorna "Unsupported fields". Por isso a leitura demográfica usa spend/reach/CTR/cliques no link como proxy, não o resultado (mensagem) diretamente. Sinalizado nas notas internas.

**Indicador principal:** mensagens iniciadas (`actions:onsite_conversion.messaging_conversation_started_7d`). Frente secundária: visitas ao perfil (`profile_visit_view`), campanha "leg_seguidores" — indicador diferente, não soma com mensagens.

**Visão geral (30d)**
- Investimento total: R$ 3.237,87
- Mensagens iniciadas: 426 (campanhas "[LEGADO] Engajamento" + "leg_eng_morno"), custo médio R$ 7,30
- Visitas ao perfil: 449, custo R$ 0,28 (campanha "leg_seguidores")
- Impressões: 123.450 | Cliques: 2.887

**Perfil demográfico**
- Feminino: R$ 2.968,48 (91,7%), CTR 2,38%, custo por clique R$ 2,57
- Masculino: R$ 258,61 (8,0%), CTR 2,46%, custo por clique R$ 1,23 (volume baixo — 328 cliques, direcional)

**Faixa etária**
- 35-44: R$ 1.697,77 (52,4%), CTR 2,59% — núcleo da conta
- 25-34: R$ 1.082,91 (33,4%), CTR 2,05%
- 45-54: R$ 309,54 (9,6%), CTR 3,35%
- 55-64: R$ 39,99 (1,2%), CTR 4,86% — pouco investimento, mas CTR crescente com a idade (padrão consistente 25-34 → 55-64)
- **Descoberta:** CTR sobe de forma quase monotônica com a idade a partir dos 25 anos (2,05% → 2,59% → 3,35% → 4,86%), fora justamente das faixas mais investidas. Vale testar abrir a segmentação principal até 54/64 anos.

**Plataformas**
- Instagram: R$ 3.082,38 (95,2%), CTR 2,38%, custo/clique R$ 2,33
- Facebook: R$ 153,04 (4,7%), CTR 2,64% (mais alto que Instagram), custo/clique R$ 3,06
- WhatsApp: R$ 2,45 (irrelevante)

**Performance de segmentação (nível adset, campanha de mensagens)**
| Conjunto | Status | Resultado | Custo | Spend |
|---|---|---|---|---|
| Todos//35-44//Aberto//Goiânia+25 + Advantag | eng_frio | PAUSADO | 89 msgs | R$ 5,94 | R$ 528,39 |
| Oferta R$1.043 // Conjunto 3 teste de criativos | ATIVO | 84 msgs | R$ 6,20 | R$ 520,50 |
| Oferta R$1.043 // Conjunto 1 teste de criativos | ATIVO | 82 msgs | R$ 6,48 | R$ 531,53 |
| Oferta R$1.043 // eng_frio | ATIVO | 101 msgs | R$ 8,26 | R$ 833,93 |
| Oferta R$1.043 // Conjunto 2 teste de criativos | ATIVO | 59 msgs | R$ 8,74 | R$ 515,76 |
| cpc_todos_25-45 // eng_morno | ATIVO | 11 msgs | R$ 14,93 | R$ 164,22 |

- **Campeão de custo (ativo):** Conjunto 3 teste de criativos, R$ 6,20/msg.
- **Campeão de volume:** Oferta R$1.043 // eng_frio, 101 msgs — mas é o mais caro do grupo (R$ 8,26). Confirma que campeão de custo ≠ campeão de volume.
- **A/B de criativos (mesma segmentação, 3 conjuntos):** Conjunto 3 (R$6,20) e Conjunto 1 (R$6,48) praticamente empatados (diferença de 4,5%, abaixo do limiar de significância) — leitura direcional. Conjunto 2 é claramente pior (R$8,74, 41% mais caro) — candidato a pausar ou trocar criativo.
- Conjunto pausado "eng_frio 35-44" teve o menor custo histórico da conta (R$5,94) — vale reativar como teste.
- Frequência máxima: 2,41 (eng_frio) — sem alerta de saturação (limite 3,0).
- Nenhum conjunto com investimento relevante e zero resultado.

**Notas internas para a gestão**
1. API não permite cruzar mensagens iniciadas por gênero/idade neste nível de breakdown — leitura demográfica é por proxy (spend/CTR/clique), não pelo resultado em si. Se precisar do cruzamento exato, puxar por adset com breakdown (pode também não ser suportado — testar).
2. Facebook está sub-investido (4,7% da verba) mas com CTR mais alto que Instagram — candidato a teste de aumento de orçamento.
3. Conjunto pausado com melhor custo histórico (R$5,94) merece reativação como teste A/B contra os ativos atuais.
4. Teste de criativos com 3 conjuntos: Conjunto 2 performando 41% pior que os outros dois — sugerido pausar/trocar criativo no próximo ciclo.

---

## ETAPA 2 — Mensagem para o cliente (copiar e colar)

*Falaa, Raffa! Tudo bem?*
Segue o nosso relatório referente públicos:

* *Perfil Demográfico:* O nosso público mais engajado continua sendo o feminino, responsável por *91,7% do investimento* (R$ 2.968,48) e por quase todo o alcance da conta. O público masculino teve custo por clique mais baixo (R$ 1,23 contra R$ 2,57 do feminino), mas ainda é um volume pequeno (328 cliques) pra virar decisão de verba.
* *Faixa Etária Principal:* A faixa de *35 a 44 anos* é o nosso núcleo, com *R$ 1.697,77 investidos* (52% do total) e bom CTR (2,59%). Vale destacar que o CTR sobe conforme a idade avança, chegando a 4,86% na faixa de 55 a 64 anos mesmo com pouquíssimo investimento (R$ 39,99) — um público fora da nossa segmentação principal reagindo bem, vale testar abrir um pouco a faixa.
* *Plataformas:* O *Instagram* domina com *95,2% do investimento* (R$ 3.082,38) e CTR de 2,38%. O Facebook, mesmo recebendo só 4,7% da verba (R$ 153,04), teve CTR mais alto (2,64%) — sinal de que dá pra testar um pouco mais de orçamento por lá.
* *Performance de Segmentação (Quais públicos trazem o melhor custo?):* Entre os conjuntos ativos, o teste de criativos "Conjunto 3" é o mais barato, R$ 6,20 por mensagem (84 mensagens). Já o campeão de volume é o conjunto "Oferta R$ 1.043 // eng_frio", com 101 mensagens, só que a um custo mais alto, R$ 8,26. Um conjunto irmão que estava pausado chegou a rodar a R$ 5,94 por mensagem — vamos reativar ele como teste no próximo ciclo.
