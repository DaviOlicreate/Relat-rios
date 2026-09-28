# Varredura de Públicos — Rodada A (últimos 30 dias)

Data da varredura: 22/09/2026
Contas: Supermercado São Luiz · Go Games Jacarepaguá · Go Games Goiânia · Mazulli Arte
Modo 2 (lote) — análise interna, não é a mensagem de WhatsApp para o cliente.

Validação: em todas as 4 contas a soma de investimento por breakdown (gênero) bateu exatamente com a soma por campanha. `results` no nível `ad_account` voltou "Not available" nas 4 contas (mix de objetivos) — números de resultado abaixo vêm do nível campanha/conjunto, como manda a regra de "Not available".

---

## 1) Supermercado São Luiz (254866402925450)

- Investimento: R$ 2.824,92 · Alcance ~68,9 mil (mulheres) + 38,9 mil (homens) · Resultado principal: mensagens no WhatsApp, 457 conversas (campanhas de messaging), custo médio ≈ R$ 4,05.
- Perfil dominante: feminino (74,3% do investimento, alcance 68.874) — CTR sobe com a idade (1,50% aos 18-24 até 3,97% aos 65+).
- Campeão de custo (mensagens): "WhatsApp | Reativação Clube LAL1%" — R$ 3,13/conversa (184 conversas).
- Campeão de volume: mesmo conjunto acima, 184 conversas (levemente à frente do "Feed Conversa", 162).
- Alerta: frequência 3,83 no conjunto "Feed Conversa" — leve saturação, ainda não urgente (< 5,0).
- Veredito: sem novidade, pode esperar — só vale revisar a frequência do "Feed Conversa" no próximo ciclo.

## 2) Go Games Jacarepaguá (524247290166854)

- Investimento: R$ 2.299,48 · Duas frentes: mensagens (WhatsApp) e leads via site/pixel.
- Perfil dominante: feminino (93,2% do investimento, R$ 2.143,40) — praticamente sem verba em público masculino.
- Campeão de custo/volume (mensagens): "Criativos estáticos... + Lista de clientes" — R$ 4,12/conversa, 252 conversas, spend R$ 1.036,98.
- Leads via site: 244 leads a R$ 4,30 (adset "24-55_lista de clientes", spend R$ 1.050,21).
- Alerta: frequência 3,12 no conjunto de mensagens líder — no limite do threshold de saturação (3,0). Descoberta: faixa 45-54 tem CTR 4,08% (2º melhor), mas recebe só 15,6% do investimento — segmento subaproveitado.
- Veredito: sem novidade urgente, mas observar frequência no próximo ciclo.

## 3) Go Games Goiânia (706269358010254)

- Investimento: R$ 4.344,61 · Alcance 45.046 (mulheres) + 14.766 (homens) · Resultado principal: mensagens no WhatsApp, 456 conversas, custo médio ≈ R$ 8,56 — quase o dobro do custo por mensagem das contas irmãs (São Luiz R$ 4,05, Jacarepaguá R$ 4,12).
- Perfil dominante: feminino (89,5% do investimento) · Idade dominante 35-44 (50,4% do investimento); CTR sobe de 1,81% (18-24) a 4,01% (65+).
- Teste A/B controlado dentro da campanha "Oferta R$ 1.043,00" (mesma faixa etária, mesmo público, só o criativo muda): Conjunto 1 converteu a R$ 7,37/conversa (214 conversas) contra R$ 8,40 do Conjunto 3 (96 conversas) e R$ 10,00 do Conjunto 2 (56 conversas) — Conjunto 1 é vencedor claro em custo e volume.
- Alerta: custo por mensagem da conta subiu para quase o dobro das contas irmãs; pior conjunto ativo é "cpc_todos_25-45_Shopping cerrado + 25km | eng_morno" a R$ 10,89/conversa (44 conversas).
- Veredito: relatório completo vale a pena agora — investigar por que o custo por mensagem dobrou frente às contas irmãs e escalar o Conjunto 1 vencedor do teste.

## 4) Mazulli Arte (302329694647309) — e-commerce

- Investimento: R$ 3.121,05 · Resultado principal: compras (pixel), 30 compras no total, custo médio muito alto e desigual entre conjuntos (R$ 57,13 / R$ 62,53 / R$ 393,88 por compra).
- Perfil dominante: feminino (93,7% do investimento, alcance 159.418) · Idade dominante 35-44 (46,8%), mas 45-54 e 55-64 têm CTR mais alto (5,53% e 7,18%) com menos verba — segmento subaproveitado.
- Campeão de custo: conjunto "Sul e Sudeste" (1085.55 gasto) a R$ 57,13/compra, 19 compras — ainda assim o mais barato do grupo de vendas.
- Pior conjunto: "Sul e Sudeste" (segunda instância, R$ 393,88) — 1 compra só, volume insuficiente para conclusão, mas já foi pausado.
- Alerta: frequência acima de 3,0 em três conjuntos de vendas ativos/recém-pausados (4,59 / 3,62 / 3,11) — sinal de fadiga de público nas campanhas de conversão, coincide com o custo por compra alto.
- Veredito: relatório completo vale a pena agora — fadiga de público nas campanhas de vendas (frequência alta + custo por compra em alta) é o ponto crítico da rodada.

---

## Quadro comparativo

| Cliente | Investimento (30d) | Resultado principal | Custo unitário | Alerta |
|---|---|---|---|---|
| Supermercado São Luiz | R$ 2.824,92 | 457 mensagens WhatsApp | ≈ R$ 4,05 | Frequência 3,83 (leve) |
| Go Games Jacarepaguá | R$ 2.299,48 | 252 mensagens (líder) + 244 leads site | R$ 4,12 msg / R$ 4,30 lead | Frequência 3,12 (leve) |
| Go Games Goiânia | R$ 4.344,61 | 456 mensagens WhatsApp | ≈ R$ 8,56 | Custo por mensagem ~2x as contas irmãs |
| Mazulli Arte | R$ 3.121,05 | 30 compras | R$ 57–394 (muito desigual) | Frequência alta (até 4,59) + custo por compra em alta |

## Prioridade da semana

1. **Go Games Goiânia** — custo por mensagem dobrou frente a São Luiz/Jacarepaguá; já há um teste A/B claro (Conjunto 1) para escalar enquanto se investiga a causa da alta.
2. **Mazulli Arte** — fadiga de público nas campanhas de vendas (frequência 3,1 a 4,6) coincide com custo por compra elevado; candidata a renovação de criativo/público antes do próximo ciclo.
3. Go Games Jacarepaguá e Supermercado São Luiz seguem estáveis; só acompanhar a frequência (ambos perto de 3,0) no próximo check.

Próximo passo sugerido: rodar o Modo 1 completo para Go Games Goiânia e Mazulli Arte.
