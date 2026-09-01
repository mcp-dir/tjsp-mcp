# Jurisprudência TJSP

### São Paulo state court case law for Claude, Cursor and AI agents

Search case law from **TJSP**, the Brazilian court with the largest body of published decisions, straight from Claude, ChatGPT or your own agent. The same connection also reaches 16 other courts, including the Supreme and Superior Courts, when your thesis does not stop in São Paulo. Free, no login, hosted by the platform.

- ⚖️ **TJSP** plus 16 other Brazilian courts on the same connection
- 🎯 **The snippet that actually MATCHED**, not the boilerplate opening every ruling shares
- 🔗 **Link to the official court site** on every result
- 📄 **Full text on demand** where the ruling allows it
- 🚦 **Says when it does not know**: an unavailable source becomes an explicit notice, never an unexplained blank
- 🔒 **Read-only**
- ⚡ **Free, no login, no credentials**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue

[Versão em português](README.md) · [Full docs (PT-BR)](docs/) · [Agent skill](skills/)

---

## One-click install

### Claude (Web and Desktop)

Anthropic unified MCP installation at `claude.ai/customize/connectors`. **The same link works for Claude Web and Claude Desktop** (just be logged in):

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (if the deeplink does not open): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → paste **Name** `Jurisprudência TJSP` and **URL** `https://api.mcp.ai/p_tjsp`.

### Cursor

[➕ Install Jurisprudência TJSP in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tjsp&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90anNwIn0=)

### VS Code (Copilot Chat)

[➕ Install Jurisprudência TJSP in VS Code](vscode:mcp/install?name=tjsp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tjsp%22%7D)

### ChatGPT, Manus, OpenClaw and 40+ other clients

Works with any MCP client that speaks **MCP over HTTP**. The server URL is always:

```
https://api.mcp.ai/p_tjsp
```

Per-client details: [INSTALL.md](INSTALL.md).

---

## Example prompts

```
TJSP case law on damages for late real-estate delivery
How has TJSP been ruling on eviction for non-payment?
Compare TJSP and the Superior Court on condo-fee limitation periods
```

---

## 3 tools available

| Tool | Description |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Details for each tool: [docs/ferramentas.md](docs/ferramentas.md) (PT-BR)

---

## Pricing

Free.

---

## Privacy & data protection

- **Read-only**, no tool changes data at the source.
- **Sub-processors**: Serper (Google Search), the LLM host you choose (Claude, ChatGPT, Cursor, your own agent). Full list in [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Data returned by the tools is sent to **the LLM host you choose**, a sub-processor outside our control. We recommend plans with training opt-out.

---

## FAQ

**O TJSP é o único tribunal?**
Não. A conexão serve 17 tribunais: além do TJSP, STF, STJ, TST, TRF3, TRF4, CARF e os TJs de RJ, MG, RS, PR, SC, CE, GO, MT, MS e MA. Restringir a busca ao TJSP é opcional, e comparar São Paulo com as cortes superiores é uma pergunta só.

**Precisa de login ou cadastro?**
Não. É grátis e sem credencial, e você não precisa de conta em nenhum tribunal.

**Serve para citar em petição?**
Serve para encontrar e ler. Todo resultado traz o link no site oficial, e a conferência lá é obrigatória antes de citar.

**Por que uma busca voltou vazia?**
Quase sempre é vocabulário: o tribunal nomeia a tese de um jeito diferente do coloquial, e a resposta sugere o que tentar. Se a fonte estiver indisponível no momento, ela diz isso explicitamente, o que é diferente de a decisão não existir.

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills, tudo MIT.


---

## Support

- 📧 [tjsp@mcp.ai](mailto:tjsp@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tjsp-mcp/issues)
- 📄 [docs/](docs/)

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_tjsp` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
