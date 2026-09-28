# Go Games Jacarepaguá — Relatório de Público (últimos 30 dias)
Data de geração: 27/08/2026 | Conta: 524247290166854 | Contato: Michelle

---

## ETAPA 1 — Análise interna (não enviar ao cliente)

**Validações**
- Soma de investimento por breakdown (gênero, idade, plataforma) bateu com o total da conta: R$ 3.095,13 nos três casos. OK.
- Conta tem dois indicadores de resultado ativos e diferentes — tratados como frentes separadas, sem soma entre eles.
- Breakdown de gênero/idade/plataforma não suporta o campo de conversas iniciadas (API retorna "Unsupported fields") — leitura demográfica usa spend/CTR/clique como proxy, não o resultado diretamente.

**Indicador principal:** mensagens iniciadas (campanha "leg_mensagens ABO_atualizado"). Frente secundária: leads via pixel do site (campanha "Campanha conversão site novo").

**Visão geral (30d)**
- Investimento total: R$ 3.095,13
- Mensagens iniciadas: 440 (R$ 2.631,28 investidos, 85% da verba), custo médio R$ 5,98
- Leads (site/pixel): 151 (R$ 463,85, 15% da verba), custo R$ 3,07
- Impressões: 154.556 | Cliques: 3.736

**Perfil demográfico**
- Feminino: R$ 2.763,55 (89,3%), CTR 2,44%, custo/clique R$ 1,85
- Masculino: R$ 323,61 (10,4%), CTR 2,21%, custo/clique R$ 1,71 (volume baixo — 189 cliques, direcional)

**Faixa etária**
- 35-44: R$ 1.710,78 (55,3%), CTR 2,40% — núcleo da conta
- 25-34: R$ 886,69 (28,6%), CTR 2,24%
- 45-54: R$ 487,96 (15,8%), CTR 3,10% — melhor CTR entre as faixas relevantes, mesmo com bem menos verba
- **Descoberta:** mesmo padrão observado na conta de Goiânia — CTR sobe com a idade (2,24% → 2,40% → 3,10%) fora do núcleo principal de segmentação. Público 45-54 pouco explorado e reagindo bem.

**Plataformas**
- Instagram: R$ 2.761,38 (89,2%), CTR 2,36%, custo/clique R$ 1,86
- Facebook: R$ 331,50 (10,7%), CTR 2,72% (mais alto que Instagram), custo/clique R$ 1,79
- Threads: R$ 2,25 (irrelevante)

**Performance de segmentação (nível adset)**

Campanha de mensagens (mesma segmentação-base "Todos//24-65+//Aberto//10km//IG e FB + Balão de preço + Lista de clientes", variando só o tipo de criativo/recorte):
| Conjunto | Status | Resultado | Custo | Spend | CTR |
|---|---|---|---|---|---|
| Criativos estáticos (mesma segmentação-base) | **ATIVO** | 82 msgs | **R$ 2,36** | R$ 193,65 | 3,41% |
| Todos//24-65+... Balão de preço + Lista de clientes | PAUSADO | 153 msgs | R$ 6,05 | R$ 925,28 | 1,89% |
| Todos//25-54/aberto//IG e FB//10km | PAUSADO | 83 msgs | R$ 5,88 | R$ 488,12 | 1,73% |
| Cópia (mesma config, nº final 62) | PAUSADO | 76 msgs | R$ 9,09 | R$ 690,83 | 1,42% |
| Mulheres//25-54/Pais//Instagram//10km | PAUSADO | 43 msgs | R$ 6,95 | R$ 298,69 | 1,69% |

Campanha de leads (site):
| Conjunto | Status | Resultado | Custo | Spend | CTR |
|---|---|---|---|---|---|
| 24-55_lista de clientes_todos_Rio + 10km | ATIVO | 151 leads | R$ 3,07 | R$ 463,23 | 4,78% |

- **Descoberta principal do mês:** o conjunto de criativos estáticos usa a mesma segmentação-base do conjunto pausado "Todos//24-65+...", isolando o criativo como única variável — e o custo caiu 61% (R$ 6,05 → R$ 2,36), com CTR quase o dobro (1,89% → 3,41%). É o único conjunto de mensagens ativo hoje e está claramente sub-investido (R$ 193,65 no período) frente ao desempenho.
- **Campeão de custo:** criativos estáticos, R$ 2,36/msg.
- **Campeão de volume (histórico, hoje pausado):** Todos//24-65+... Balão de preço, 153 msgs a R$ 6,05.
- Frequência máxima: 2,40 (criativos estáticos) e 2,29 (leads) — sem alerta de saturação.
- Conjunto "Novo conjunto de Engajamento" (pausado): R$ 34,71 gastos por só 3 mensagens (R$ 11,57/msg) — volume baixo demais para conclusão, mas performance ruim; não escalar.

**Notas internas para a gestão**
1. Achado forte: escalar o conjunto de criativos estáticos — mesma segmentação do conjunto pausado, custo 61% menor. Prioridade para o próximo ciclo.
2. Hoje só um conjunto de mensagens está ativo (criativos estáticos, R$ 193,65) — verba da campanha de mensagens está concentrada demais num único conjunto pequeno; considerar reativar um segundo conjunto com criativo estático para dar volume sem perder o custo.
3. Frente de leads (site) rodando bem, sem alertas — CTR 4,78%, custo R$ 3,07/lead.
4. Mesmo padrão de CTR subindo com a idade (45-54) observado também na conta de Goiânia — pode valer testar em ambas as contas ao mesmo tempo.
5. API não permite cruzar mensagens por gênero/idade neste nível — leitura demográfica é por proxy (spend/CTR/clique).

---

## ETAPA 2 — Mensagem para o cliente (copiar e colar)

*Falaa, Michelle! Tudo bem?*
Segue o nosso relatório referente públicos:

* *Perfil Demográfico:* O público feminino segue sendo o motor da conta, com *89,3% do investimento* (R$ 2.763,55) e alcance de quase 39 mil mulheres. Os homens tiveram custo por clique um pouco menor (R$ 1,71 contra R$ 1,85), mas ainda é uma base pequena (189 cliques) pra virar decisão de verba.
* *Faixa Etária Principal:* A faixa de *35 a 44 anos* concentra *55,3% do investimento* (R$ 1.710,78) e é o nosso núcleo de resultado. A faixa de 45 a 54 anos, mesmo recebendo bem menos verba (15,8%, R$ 487,96), teve o melhor CTR da conta (3,10% contra 2,40% da faixa principal) — um público que reage bem e está sendo pouco explorado.
* *Plataformas:* O *Instagram* concentra *89,2% do investimento* (R$ 2.761,38) com CTR de 2,36%. O Facebook, com só 10,7% da verba (R$ 331,50), teve CTR mais alto (2,72%) — outro indício de que dá pra testar mais orçamento por lá.
* *Performance de Segmentação (Quais públicos trazem o melhor custo?):* O grande destaque do mês é o conjunto com *criativos estáticos*, que usa a mesma segmentação de um conjunto irmão que já rodou — só muda o formato do criativo. Ele trouxe 82 mensagens a *R$ 2,36* cada, quase 3x mais barato que o conjunto irmão (R$ 6,05). Vamos escalar esse formato no próximo ciclo. Já na frente de leads pelo site, o conjunto "24-55 // Lista de clientes // Rio + 10km" trouxe 151 leads a R$ 3,07, com ótimo CTR (4,78%).
