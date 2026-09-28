# Relatórios — Legado Digital

Cada pasta corresponde a uma **rotina agendada** do Claude (mesmo nome da rotina).
Dentro dela, uma pasta por **data de envio** (`AAAA-MM-DD`) e um arquivo por **cliente**.

| Pasta | Rotina | Quando roda |
|---|---|---|
| `1-relatorio-de-criativos/` | Relatório de criativos | seg, ter, qui, sex |
| `2-relatorio-de-publicos/` | Relatório de públicos | seg, ter, qui, sex |
| `3-relatorio-semanal-de-metricas/` | Relatório semanal de métricas 2.0 | seg, ter, qui, sex |
| `4-relatorio-de-concorrencia/` | Relatório Mensal de Concorrência | dia 20 de cada mês |
| `5-linktree/` | Modelo e instruções do Gem de Linktree | — |
| `6-relatorios-avulsos/` | Relatórios pedidos manualmente | — |

Exemplo: `1-relatorio-de-criativos/2026-09-21/go-games-goiania.md`

Arquivos que começam com `_` (ex.: `_varredura-interna.md`) são análises internas com várias contas e não vão para o cliente.

`CLAUDE.md` contém as regras gerais usadas pelas rotinas.

## Regra para as rotinas
- Salvar sempre direto na branch `main` (nunca criar branch nova).
- Mensagem do commit: `[Nome da rotina] AAAA-MM-DD — clientes`.
