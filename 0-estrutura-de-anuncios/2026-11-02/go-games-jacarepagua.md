## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Oii, pessoal! Tudo bem? Segue como está hoje a estrutura dos seus anúncios:

📋 Campanhas ativas
━━━━━━━━━━━━━
- 2 campanhas ativas, com 1 conjunto de anúncios em cada, somando R$ 60,00 por dia (R$ 30,00 em cada)
- Campanha de mensagens: leva a pessoa direto para o WhatsApp (285 conversas iniciadas nos últimos 30 dias, a R$ 4,83 cada). Verba definida no conjunto de anúncios
- Campanha do site novo: gera cadastros pelo site (222 cadastros, a R$ 5,89 cada). Verba definida na própria campanha

🎯 Públicos
━━━━━━━━━━━━━
- Região: raio de 10 km ao redor do Center Shopping Rio, nas duas campanhas. Idade de 25 a 54 anos nas mensagens e de 24 a 55 anos no site, todos os gêneros
- Usamos o público da lista de clientes da Go Games e um público parecido com ela (1% mais semelhante). Hoje não temos público de quem já interagiu com o Instagram ou visitou o site, nem exclusões de quem já é cliente

🎨 Criativos
━━━━━━━━━━━━━
- 17 anúncios ativos: 16 nas mensagens (9 imagens e 7 vídeos) e só 1 no site novo (vídeo)
- A mensagem principal é "festa completa e sem estresse, datas esgotam rápido", com preço a partir de R$ 792,00 nos vídeos e a partir de R$ 1.000 em 5x nas imagens. Botão de Enviar mensagem no WhatsApp nas mensagens e Saiba mais no site

💬 Nossa leitura
━━━━━━━━━━━━━
Está bom: custo por conversa baixo e variedade grande de criativos, com a imagem de feed liderando (R$ 2,65 por mensagem). Vamos ajustar: o público das mensagens está vendo o anúncio vezes demais (frequência 3,31), o site depende de um único anúncio e os preços divergentes (R$ 792 x R$ 1.000) precisam ser alinhados.

Qualquer dúvida, tô à disposição.
```

## ANÁLISE INTERNA (não enviar)

Período: últimos 30 dias (filtro: apenas ACTIVE). Dados via Meta Ads MCP, conta 524247290166854.

| Campanha (objetivo) | Conjunto | Anúncios ativos | Resultado 30d | Verba diária | Gasto 30d | Freq. |
|---|---|---|---|---|---|---|
| leg_mensagens ABO_atualizado (Engajamento / mensagens, orçamento no conjunto) | Criativos estáticos - Todos//24-65+/Aberto//10km//IG e FB + Balão de preço + Lista de clientes (CONVERSATIONS, WhatsApp) | 16 (9 imagem, 7 vídeo) | 285 mensagens iniciadas, R$ 4,83 | R$ 30,00 | R$ 1.377,08 | 3,31 |
| Campanha conversão site novo (Leads, orçamento na campanha, maior volume) | 24-55_lista de clientes_todos_Rio + 10km (OFFSITE_CONVERSIONS, evento lead do pixel) | 1 (vídeo) | 222 leads (pixel), R$ 5,89 | R$ 30,00 | R$ 1.308,50 | 2,81 |

Totais: 2 campanhas, 2 conjuntos, 17 anúncios ativos, R$ 60,00/dia.

Observações técnicas:
1. Sobreposição de público: os dois conjuntos usam a mesma lista de clientes + lookalike 1% e o mesmo raio de 10 km do Center Shopping Rio, com idade quase igual (25-54 x 24-55). Competem no mesmo leilão (e no mesmo orçamento total de R$ 60). O conjunto do site tem a expansão de lookalike/custom ligada e posicionamentos abertos (inclui WhatsApp Status e Threads); o de mensagens só IG e FB, mobile. Advantage+ público desligado em ambos.
2. Frequência 3,31 no conjunto de mensagens (acima de 3,0) com público pequeno (lista + lookalike em 10 km). Sinal de saturação; o nome do conjunto diz "24-65+" mas a segmentação real é 25-54 (nomenclatura desatualizada). Sem público frio amplo nem público quente de engajamento/visitantes do site. Sem exclusão de clientes/convertidos.
3. Conjunto do site com 1 único anúncio ativo (Ad 3 site novo, vídeo, CTR 2,12%, 73 leads a R$ 5,66), responsável por R$ 413 dos R$ 1.308 gastos: risco de fadiga e sem teste. Criativo com CTA Saiba mais e promessa "20% OFF a partir de R$ 792".
4. Mensagens: 16 anúncios, mas gasto concentrado: o líder (Fazer a festa do seu filho, vídeo, R$ 431,85, 80 msgs, R$ 5,40, CTR 1,23%) tem 31% do gasto; "Ad 6 Rio C Feed" (imagem) é o mais eficiente com volume: 79 msgs a R$ 2,65 (CTR 2,72%) com R$ 209; "Ad 5 Rio C Story" 42 msgs a R$ 4,53. Pelo menos 9 anúncios com menos de R$ 20 de gasto e 1 a 3 resultados (volume insuficiente para conclusão; direcional). "Ad 4 Rio b feed" (R$ 3,66) sem resultado atribuído. Vários anúncios são cópias (Ad 7 Rio D Story e cópia, "Fazer a festa... Cópia"), pulverizando a verba.
5. Mensagem inconsistente de preço: vídeos dizem "a partir de R$ 792,00" e imagens "a partir de R$ 1.000 em 5x". Alinhar a oferta (pode ser promoção vs. preço cheio, confirmar com o cliente).
6. Consistência dos dados: a soma dos resultados por anúncio ativo nas mensagens (258) não bate com o total da campanha (285), e o único anúncio do site mostra 73 dos 222 leads. A diferença é compatível com anúncios já pausados que geraram resultados no período (a coleta filtrou só ativos). Não corrigido nem estimado.
7. Próximo passo concreto: (a) trocar/ampliar o público das mensagens (testar aberto/Advantage+ sem lista, ou ampliar raio) para derrubar frequência; (b) excluir a lista de clientes do conjunto do site ou diferenciar os públicos para evitar competição; (c) subir 2 a 3 novos criativos no site; (d) concentrar mensagens nos 4 a 5 melhores e pausar os de gasto residual.

Erros de API: nenhum. O bloco next_actions (tendência/benchmark) foi ignorado conforme o spec.
