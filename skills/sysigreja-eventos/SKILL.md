---
name: sysigreja-eventos
description: Consultar eventos e inscritos da igreja no SysIgreja via MCP. Use quando o usuário perguntar de evento, vagas, resumo ou uma pessoa inscrita.
---

# SysIgreja Eventos

Comece por `minha_sessao`. Se `precisaEscolherOrg`, chame `escolher_organizacao`.

- Liste eventos com `listar_meus_eventos` (igreja) ou `listar_eventos` (Master).
- Resumo: `resumo_evento` com `eventoId`. Não invente `loginId`.
- Pessoa: `buscar_inscrito` com `eventoId` + nome/e-mail (mín. 3 letras). Depois `inscrito_detalhe` se precisar da ficha.
- Não peça a lista completa de inscritos.
- Não use tools de receita, Mercado Pago, flags ou orgs globais se não forem Master.
- Não invente dados: se a tool recusar, explique a permissão.

Privacidade: https://sysigreja.com/privacidade
Termos: https://sysigreja.com/termos
