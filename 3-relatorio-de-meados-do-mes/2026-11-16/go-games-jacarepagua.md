# Go Games Jacarepaguá — relatório de meados do mês

Janela atual: 09/11 a 15/11 (7 dias). Comparação: 02/11 a 08/11 (7 dias). Fonte: Meta Ads (MCP), nível campanha, dados puxados em 16/11/2026.

> **VERIFICAR ANTES DE ENVIAR:** o investimento caiu 10,8% (R$ 656,22 para R$ 585,29), todo na "Campanha conversão site novo" (-28,9%). Confirme se foi corte intencional. Confira também o site e o pixel (ver análise): os cliques subiram de proporção, mas os leads do site caíram pela metade.

## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Olá pessoal! Tudo bem?

Pessoal, estou enviando aqui o relatório dos últimos 7 dias de campanhas (09/11 a 15/11):

---

✅ *Resumo:*

* *Valor TOTAL investido:* R$ 585,29 (-10,8% que a semana anterior)
* *Impressões/Visualizações:* 34.748 (-27,1% que a semana anterior)
* *CPM (Custo para cada 1mil visualizações):* R$ 16,84 (+22,3% que a semana anterior)
* *Cliques:* 797 (-12,4% que a semana anterior)
* *CTR (Taxa de Cliques):* 2,29% (+20,1% que a semana anterior)
* *Número de contatos pelos anúncios:* 78 (-23,5% que a semana anterior)
* *Média de contatos por dia:* 11,14
* *Custo por lead:* R$ 7,50 (+16,6% que a semana anterior)

💡 Comentários:

Investimos R$ 585,29 esta semana e geramos 78 contatos, com custo médio de R$ 7,50 cada. O volume caiu por causa dos cadastros pelo site, que vieram em menor número, enquanto a campanha de WhatsApp cresceu de 50 para 55 mensagens e ficou um pouco mais barata (R$ 6,41 cada), então o ajuste agora é revisar a página e os anúncios da campanha do site.

Vamos continuar monitorando a qualidade e ajustando as campanhas para melhorar a performance, sempre com o objetivo de escalar os resultados.

Gostaria de saber de vocês qual foi a percepção referente ao desempenho na semana e nas últimas mudanças.
```

## ANÁLISE INTERNA (não enviar)

### Composição

| Campanha | Indicador | Atual (09/11–15/11) | Anterior (02/11–08/11) |
|---|---|---|---|
| Campanha conversão site novo | Leads (pixel) | 23 · R$ 232,87 · **R$ 10,12** | 52 · R$ 327,68 · R$ 6,30 |
| leg_mensagens ABO_atualizado | Mensagens | 55 · R$ 352,42 · R$ 6,41 | 50 · R$ 328,54 · R$ 6,57 |

- Contatos (mensagens + leads de pixel): 78 contra 102 (-23,5%). Sem verba fora de contato, então custo limpo = custo total (R$ 7,50 contra R$ 6,43, +16,6%).

### Leitura
- **Fato:** na campanha do site, o CTR subiu de 1,93% para 2,58%, mas a taxa de lead por clique caiu de 10,3% (52/507) para 5,8% (23/397). O problema está depois do clique, não no anúncio.
- **Hipótese:** página do site lenta/fora do ar em algum momento, formulário com erro, ou pixel de lead disparando menos. Testar o formulário e conferir o evento Lead no Gerenciador de Eventos.
- **Fato:** CPM da conta +22,3% (o da campanha do site +20,9%) — leilão mais caro, comum na semana pré-Black Friday.
- Mensagens estáveis: diferença de custo de -2,4%, dentro do ruído.

### Notas técnicas
- A "Campanha conversão site novo" tem `attribution_setting: multiple` e o campo `lead` (24) difere de `results` (23) por 1. Usado `results`.
- O campo `lead` = 1 e `omni_purchase` = 1 na campanha de mensagens da semana anterior: ignorados (indicador é mensagens).
- Validações OK (custo por resultado e CTR coerentes).
