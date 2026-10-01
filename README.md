# SysIgreja — plugin MCP

Conector único. O servidor decide as tools pelo login (Master = backoffice; adm da igreja = eventos).

**Privacidade:** https://sysigreja.com/privacidade  
**Termos:** https://sysigreja.com/termos  
**MCP:** https://backend.sysigreja.com/mcp/admin

## Instalar

1. Instale este plugin (Cursor Marketplace / cursor.directory, ou copie a pasta para `~/.cursor/plugins/local/sysigreja`).
2. Conecte — o navegador abre o login SysIgreja.
3. Escolha a igreja se tiver mais de uma.

Não coloque senha no `mcp.json`.

Equipe interna pode continuar com Basic no `.cursor/mcp.json` do repositório (não é este plugin).

## Publicar (lojas)

Este diretório é a **casca** (manifest + skill). O backend Nest permanece privado.

Repositório público: https://github.com/fereinaux/sysigreja-mcp

1. **Cursor (community):** https://cursor.directory/plugins/new — cole a URL deste repo
2. **Cursor (oficial):** https://cursor.com/marketplace/publish
3. **Claude:** https://platform.claude.com/plugins/submit
4. **ChatGPT:** rascunho With MCP no portal OpenAI — scan das tools depois que o OAuth estiver no ar em produção

Site: https://sysigreja.com
