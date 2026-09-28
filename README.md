# Relatórios — Legado Digital

Cada pasta corresponde a uma **rotina agendada** do Claude (mesmo nome da rotina).
Dentro dela, uma pasta por **data de envio** (`AAAA-MM-DD`) e um arquivo por **cliente**.

| Pasta | Rotina | Quando roda (3h–4h30 da manhã) |
|---|---|---|
| `1-relatorio-de-criativos/` | Relatório de criativos | 2ª e 4ª segunda-feira do mês |
| `2-relatorio-de-publicos/` | Relatório de públicos (todos os clientes) | última segunda-feira do mês |
| `3-relatorio-de-meados-do-mes/` | Relatório de meados do mês (métricas) | 3ª segunda-feira do mês |
| `4-acoes-comerciais-e-concorrentes/` | Ações comerciais e concorrentes | 3ª quinta-feira do mês |
| `5-linktree/` | Modelo e instruções do Gem de Linktree | — |
| `6-relatorios-avulsos/` | Relatórios pedidos manualmente | — |

Exemplo: `1-relatorio-de-criativos/2026-09-21/go-games-goiania.md`

Arquivos que começam com `_` (ex.: `_varredura-interna.md`) são análises internas com várias contas e não vão para o cliente.

`CLAUDE.md` contém as regras gerais usadas pelas rotinas.

## Regra para as rotinas
- Salvar sempre direto na branch `main` (nunca criar branch nova).
- Mensagem do commit: `[Nome da rotina] AAAA-MM-DD — clientes`.
