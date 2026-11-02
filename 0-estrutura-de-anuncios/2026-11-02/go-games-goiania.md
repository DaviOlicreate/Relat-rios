## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Oii, pessoal! Tudo bem? Segue como está hoje a estrutura dos seus anúncios:

📋 Campanhas ativas
━━━━━━━━━━━━━
- 3 campanhas ativas, com 4 conjuntos de anúncios e 28 anúncios, somando R$ 77,00 de verba por dia (definida em cada conjunto).
- 2 campanhas buscam conversas no WhatsApp para festas (uma para público que já conhece a Go Games, outra com teste de criativos para público aberto) e 1 busca visitas ao perfil do Instagram.

🎯 Públicos
━━━━━━━━━━━━━
- Quem já conhece vocês: pessoas de 25 a 55 anos num raio de 25 km do Shopping Cerrado, incluindo quem visitou o perfil, interagiu no Instagram, viu os vídeos e visitou o site. Clientes que já constam na sua lista ficam de fora.
- Público aberto: Goiânia e 25 km ao redor, mães e pais de 35 a 44 anos, mais a lista de clientes e um público parecido com ela. Quem já interagiu com vocês é excluído para não pagar duas vezes pela mesma pessoa.
- Visitas ao perfil: pessoas de 25 a 45 anos perto do Shopping Cerrado, só no Instagram.

🎨 Criativos
━━━━━━━━━━━━━
- 28 anúncios ativos, entre imagens e vídeos. A mensagem principal é festa tudo incluso a partir de R$ 1.117,50 no Shopping Cerrado, com apelos como "não precisa ser cara", "não feche antes de ver isso" e Dia das Crianças.
- A maioria usa o botão de enviar mensagem no WhatsApp (convite para digitar QUERO). Os anúncios de visitas ao perfil usam o botão de ver o perfil no Instagram.

💬 Nossa leitura
━━━━━━━━━━━━━
Bom: estrutura organizada, com público de quem já conhece, público aberto e visitas ao perfil, e anúncios com preço claro e botão direto para o WhatsApp. Vamos ajustar: o público de quem já conhece está vendo os anúncios vezes demais (frequência 5,79) e alguns anúncios têm pouco ou nenhum resultado, então vamos renovar e enxugar.

Qualquer dúvida, tô à disposição.
```

## ANÁLISE INTERNA (não enviar)

Período dos números: últimos 30 dias, só entidades ativas. Investimento das 3 campanhas ativas: R$ 4.347,25. Orçamento diário total: R$ 77,00, todo no nível do conjunto (nenhuma campanha tem orçamento próprio).

| Campanha (objetivo) | Conjunto | Anúncios | Verba/dia | Gasto 30d | Resultado 30d | Freq. |
|---|---|---|---|---|---|---|
| leg_eng_morno (engajamento, WhatsApp) | cpc_todos_25-45_Shopping Cerrado+25km (cópia) | 9 | R$ 30 | R$ 2.029,78 | 227 mensagens, R$ 8,94 | 5,79 |
| [LEGADO] Engajamento p/ WhatsApp (teste de criativos) | Conjunto 1 (35-44, aberto, Goiânia+25) | 11 | R$ 25 | R$ 943,43 | 143 mensagens, R$ 6,60 | 1,95 |
| mesma campanha | Conjunto 2 (idêntico ao 1) | 3 | R$ 15 | R$ 739,08 | 96 mensagens, R$ 7,70 | 2,15 |
| leg_seguidores (tráfego, perfil IG) | Todos 25-45 aberto, só Instagram | 5 | R$ 7 | R$ 379,25 | 1.400 visitas ao perfil, R$ 0,27 | 1,61 |

Observações técnicas:
- Frequência de 5,79 no conjunto de público morno (limite do spec: 3,0). Público pequeno e saturado, com 9 anúncios espalhando R$ 2.030 em 30 dias. Custo por mensagem (R$ 8,94) é o pior das campanhas de mensagens. Próximo passo: renovar criativos desse conjunto e testar expandir a janela/volume do público.
- Conjuntos 1 e 2 têm targeting idêntico (mesma idade, região, lista de clientes + semelhante 1%, mesmas exclusões), competem entre si no leilão e dividem a verba em R$ 25/R$ 15 sem motivo de teste de público. Conjunto 1 tem 11 anúncios, mas gasto concentrado em 1 deles (Ad F feed, R$ 435,50, 84 mensagens a R$ 5,18); sete anúncios têm menos de R$ 21 e 4 sem resultado disponível (Ad C, I, D, G; R$ 0,06 a R$ 1,08). Próximo passo: pausar esses anúncios e fundir os conjuntos 1 e 2.
- Sobreposição provável: o conjunto morno (25-55, 25 km do Shopping Cerrado) e o de seguidores (25-45, aberto, mesma região) sem exclusão do público de visitantes do perfil no segundo; os dois conjuntos de teste (Goiânia+25) cobrem a mesma área. Usa lista de clientes como público incluído nos conjuntos 1 e 2 (e como exclusão no morno): confirmar se é intencional, pois tende a gastar verba em quem já é cliente.
- Criativos: anúncios "Dia das Crianças R$ 1.043" ainda ativos (promoção datada, hoje 02/11) e anúncio "Ad 2 imagem" com R$ 130,78 e 8 mensagens a R$ 16,35; "Vem se divertir" a R$ 12,21 e R$ 11,60 em dois conjuntos. Melhores custos com volume razoável: Ad F feed (R$ 5,18), Ad 7 Dia das Crianças (R$ 6,03; 28 mensagens), Goiânia 2 (R$ 5,76; 12). Atenção: preços divergem nos textos (R$ 1.117,50, R$ 1.119, R$ 1.190, R$ 1.043, "R$ 1.17" no nome); padronizar a oferta. Dois anúncios do morno usam botão "Saiba mais" (AD Público morno 1) em vez de WhatsApp.
- Campanha de seguidores: custo baixo (R$ 0,27 por visita), mas o resultado é visita, não seguidor; verba de só R$ 7/dia. Um anúncio (ad 01) concentra R$ 342,67 de R$ 379,25.

Erros de API: nenhum.
