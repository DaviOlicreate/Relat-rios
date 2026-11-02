## MENSAGEM PARA O WHATSAPP DO CLIENTE (copiar e colar)

```
Oii, pessoal! Tudo bem? Segue como está hoje a estrutura dos seus anúncios:

📋 Campanhas ativas
━━━━━━━━━━━━━
- 4 campanhas, cada uma com 1 conjunto de anúncios, somando R$ 90,00 por dia
- 3 de vendas no site: uma de público frio (R$ 22/dia), uma de catálogo de produtos (R$ 22/dia) e uma otimizada por retorno sobre o investimento (R$ 40/dia, orçamento definido na campanha)
- 1 para levar gente ao perfil do Instagram (R$ 6/dia): 1.193 visitas ao perfil em 30 dias, a R$ 0,22 cada

🎯 Públicos
━━━━━━━━━━━━━
- Vendas público frio: Brasil todo, 20 a 55 anos, interesse em confeitaria, com exclusão de quem já comprou ou está na lista de clientes
- Catálogo: mulheres de 35 a 65 anos em São Paulo, interesses em confeitaria, artesanato e receitas, com o Meta ampliando o público automaticamente
- Retorno sobre investimento: Brasil todo, público aberto deixado a cargo do Meta; perfil: Instagram, 30 a 65 anos, interesses em artesanato, confeitaria e bolos
- Não temos hoje nenhum público de quem já visitou o site ou o perfil, nem público parecido com seus clientes

🎨 Criativos
━━━━━━━━━━━━━
- 25 anúncios ativos: 14 no público frio, 7 no perfil, 2 no catálogo e 2 no retorno sobre investimento
- Formatos: vídeos (perfil e retorno), anúncios de catálogo/produtos e imagens; botão quase sempre "Comprar agora" (e "Ver perfil" nos anúncios de perfil)
- Mensagens: moldes para acabamento profissional, antes e depois, kit com 5 itens, cupom de 10% para primeira compra e, em vários, a Live de Natal de 09 de outubro

💬 Nossa leitura
━━━━━━━━━━━━━
Bom: estrutura enxuta, frequência saudável (entre 1,36 e 2,55) e o perfil gerando visitas baratas. Vamos ajustar: tirar do ar os anúncios da Live de 09/10, que já passou, e criar públicos de quem já interagiu com a loja; o catálogo está caro (R$ 82,52 por compra).

Qualquer dúvida, tô à disposição.
```

## ANÁLISE INTERNA (não enviar)

Coleta: 4 chamadas OK (campaign, adset, ad, creatives), últimos 30 dias, client_conversation_id Kq7Zr2LmX9aPv4TbN8cW. Sem erros de API. Ignorei next_actions conforme spec.

| Campanha | Conjunto | Anúncios ativos | Objetivo / resultado (30d) | Verba diária | Gasto 30d |
|---|---|---|---|---|---|
| leg_conv_frio_backup | cpc_vendas_25-45_mulheres_IG & FB, Brasil teste de localização | 14 | Vendas / 16 compras, R$ 44,36 | R$ 22 (conjunto) | R$ 709,74 |
| [vendas]_advantag_catálogo | Campanha de compras_catálogo advantag | 2 | Vendas catálogo / 8 compras, R$ 82,52 | R$ 22 (conjunto) | R$ 660,12 |
| leg_seguidores_mazulli | frio_ig | 7 | Tráfego perfil IG / 1.193 visitas ao perfil, R$ 0,22 | R$ 6 (conjunto) | R$ 262,88 |
| leg_mazulli_vendas ROAS | leg_roas_adv+_brasil | 2 | Vendas, meta de ROAS / 2 compras, R$ 94,71 | R$ 40 (campanha) | R$ 189,42 |

Total: 4 campanhas, 4 conjuntos, 25 anúncios, R$ 90/dia. Frequência 30d: 2,01 / 2,19 / 1,36 / 2,55 (nenhuma acima de 3,0).

Observações técnicas:
- Gasto 30d total R$ 1.822,16 (média R$ 60,74/dia), abaixo dos R$ 90/dia atuais: orçamentos foram alterados ou campanhas entraram no período; histórico de orçamento não verificado.
- Sobreposição: as 3 campanhas de vendas miram confeitaria/mulheres no Brasil (frio Brasil 20-55, catálogo SP 35-65 com Advantage+ público, ROAS Brasil aberto com Advantage+). Competem entre si no leilão. Só o frio exclui compradores (4 listas); catálogo e ROAS não têm exclusão de clientes, então pagam para impressionar quem já comprou.
- Sem funil: não há público quente (visitantes, carrinho, engajados, 60-90d) nem semelhantes ativos. Há uma campanha antiga "[VENDAS] [CONVERSÃO] [PERPÉTUO]" (conjunto "01 - Lookalike 1% da Lista de Compradores") com 4 anúncios que aparecem como ativos no nível do anúncio, com gasto zero; a campanha não retornou como ativa. Provável anúncio ativo dentro de campanha/conjunto pausado. Vale reativar ou limpar.
- Criativo cansado/vencido: vários anúncios do conjunto frio (série Natal) divulgam "Live 09 de outubro, 15h" e "50% OFF" (0005 a 0010 Natal, 00011, Imagem natal), data já passada em 02/11. Pausar ou trocar por Natal com data atual/oferta vigente. Trio de melhores custos no frio: "0010 - Outubro NATAL 7" (3 compras, R$ 10,01), "ad 5 5 itens" (2, R$ 19,13), "Ad ursinhos" (2, R$ 28,16), mas volume baixo (direcional).
- Conjunto do catálogo: R$ 660,12 e 8 compras (R$ 82,52). Só 2 anúncios ativos, quase todo o gasto em 1 ("Novo anúncio de Vendas": R$ 276,68, 1 compra atribuída no nível do anúncio; o restante do gasto do conjunto está em anúncios que já não estão ativos). CTR alto (3,34%) e conversão fraca: olhar preço/página de produto. Cópia (R$ 9) quase sem entrega.
- Perfil: 7 anúncios com o mesmo texto e CTA, só muda o vídeo; AD 0005 concentra R$ 213,57 (81%) e 1.002 das visitas. Resultado é visita ao perfil, não seguidores (o dado de seguidores não foi puxado). Não comparar com CPA de vendas.
- ROAS: só 2 compras em R$ 189,42; sem 50 conversões/semana a otimização por valor não sai da fase de aprendizado com R$ 40/dia. Volume insuficiente para conclusão definitiva.
- Próximo passo concreto: (1) pausar criativos da Live de 09/10; (2) adicionar exclusão de compradores no catálogo e no ROAS; (3) consolidar as 3 campanhas de vendas em no máximo 2 e criar remarketing (visitantes 30d / engajados Instagram) e semelhante de compradores; (4) subir 2 a 3 criativos novos no catálogo.
