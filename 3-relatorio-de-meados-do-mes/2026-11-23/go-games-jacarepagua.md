# Go Games Jacarepaguá — relatório de meados do mês

Janela atual: 16/11 a 22/11 (7 dias). Comparação: 09/11 a 15/11 (7 dias). Fonte: Meta Ads (MCP), nível campanha, dados puxados em 23/11/2026.

> **SITUAÇÃO (23/11):** a campanha de conversão do site **parou de registrar leads a partir de 17/11** (só 1 lead na semana, contra 23 na anterior), mesmo com cliques normais (406 contra 397); as visualizações da página de destino sumiram no mesmo dia. O Davi já fez ajustes no site (troca da imagem do Hero). Falta checar o Pixel no Gerenciador de Eventos / Pixel Helper para confirmar se é contagem ou outra causa. A mensagem abaixo já traz esse contexto ao cliente.

## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Olá pessoal! Tudo bem?

Pessoal, estou enviando aqui o relatório dos últimos 7 dias de campanhas (16/11 a 22/11):

---

✅ *Resumo:*

* *Valor TOTAL investido:* R$ 568,46 (-2,9% que a semana anterior)
* *Impressões/Visualizações:* 36.478 (+5,0% que a semana anterior)
* *CPM (Custo para cada 1mil visualizações):* R$ 15,58 (-7,5% que a semana anterior)
* *Cliques:* 769 (-3,5% que a semana anterior)
* *CTR (Taxa de Cliques):* 2,11% (-8,1% que a semana anterior)
* *Número de contatos pelos anúncios:* 43 (-44,9% que a semana anterior)
* *Média de contatos por dia:* 6,14
* *Custo por lead:* R$ 13,22 (+76,2% que a semana anterior)

💡 Comentários:

Investimos R$ 568,46 esta semana e geramos 43 contatos, com custo médio de R$ 13,22 cada. No WhatsApp foram 42 conversas; já os cadastros pelo site deixaram de aparecer nos dados a partir do dia 17, mesmo com a campanha recebendo cliques normalmente. Já fiz alguns ajustes no site, incluindo a troca da imagem principal da página, e agora estou verificando o Pixel (a ferramenta que registra os cadastros do site). O custo por contato subiu nesta semana e estou examinando para saber se é de fato o Pixel ou se pode ser outra coisa.

Vamos continuar monitorando a qualidade e ajustando as campanhas para melhorar a performance, sempre com o objetivo de escalar os resultados.

Gostaria de saber de vocês qual foi a percepção referente ao desempenho na semana e nas últimas mudanças.
```

## ANÁLISE INTERNA (não enviar)

### Composição

| Campanha | Indicador | Atual (16/11–22/11) | Anterior (09/11–15/11) |
|---|---|---|---|
| Campanha conversão site novo | Leads (pixel) | 1 · R$ 223,88 · R$ 223,88 | 23 · R$ 232,91 · R$ 10,13 |
| leg_mensagens ABO_atualizado | Mensagens | 42 · R$ 344,58 · **R$ 8,20** | 55 · R$ 352,45 · R$ 6,41 |

### Dia a dia da campanha do site

| Dia | Investido | Cliques | Visualizações da página | Leads pixel |
|---|---|---|---|---|
| 09/11 | R$ 50,17 | 68 | 43 | 7 |
| 10/11 | R$ 23,87 | 32 | 17 | 4 |
| 11/11 | R$ 0,00 | 0 | Dado não disponível | Dado não disponível |
| 12/11 | R$ 37,20 | 42 | 23 | 1 |
| 13/11 | R$ 43,56 | 70 | 39 | 1 |
| 14/11 | R$ 30,70 | 78 | 48 | 4 |
| 15/11 | R$ 47,41 | 107 | 65 | 6 |
| 16/11 | R$ 29,36 | 79 | 35 | 1 |
| 17/11 | R$ 39,00 | 106 | Dado não disponível | Dado não disponível |
| 18/11 | R$ 33,87 | 81 | 1 | Dado não disponível |
| 19/11 | R$ 20,78 | 41 | Dado não disponível | Dado não disponível |
| 20/11 | R$ 0,00 | 0 | Dado não disponível | Dado não disponível |
| 21/11 | R$ 52,51 | 53 | Dado não disponível | Dado não disponível |
| 22/11 | R$ 48,36 | 46 | Dado não disponível | Dado não disponível |

### Leitura
- **Fato:** desde 17/11 a campanha do site gastou R$ 194,52 e gerou 327 cliques sem nenhum lead e praticamente nenhuma visualização de página registrada. Os dois eventos sumiram juntos, o que é típico de pixel removido/quebrado (site novo, troca de tema, domínio, consentimento de cookies). **Hipótese forte, a confirmar no Gerenciador de Eventos.**
- **Feito (Davi, 23/11):** ajustes no site, incluindo troca da imagem do Hero.
- **Pendente:** testar com o Meta Pixel Helper e checar o Gerenciador de Eventos (evento Lead e PageView). Enquanto não corrigir, a campanha otimiza "às cegas" — considere pausar.
- Na mensagem ao cliente, o custo é citado sem tom de problema, a pedido do Davi (alta de custo = em análise: Pixel ou outra causa).
- **Fato:** dias 11/11 e 20/11 com gasto zero na campanha do site (possível programação ou limite). Verificar.
- **Fato:** a campanha de mensagens piorou: 55 → 42 conversas, custo R$ 6,41 → R$ 8,20 (+27,9%), CTR 2,07% → 1,73%. Sinal de desgaste de criativo.
- Custo por contato da conta sem o site: R$ 8,20 (só mensagens).

### Notas técnicas
- Investimento -2,9% (dentro do limite de 10%).
- A campanha do site usa atribuição "multiple"; a de mensagens, 1d_view_7d_click.
- Validações: custo por resultado do Meta = investimento ÷ resultados nas duas campanhas; cliques ÷ impressões = CTR reportado. CPM e CTR da conta recalculados a partir dos totais.
