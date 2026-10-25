# Why tenon

| | **tenon** | Claude Code | Aider | OpenCode | Mistral Vibe |
|---|---|---|---|---|---|
| Licence | EUPL-1.2 | Proprietary | Apache-2.0 | MIT | Apache-2.0 |
| European and local providers built in | ✅ | — | via LiteLLM | via 75+ providers | Mistral |
| Consent before data leaves the EU | ✅ | — | — | — | — |
| Approval before writes and commands | ✅ by default | ✅ | partial | configurable | ✅ |
| System sandbox for commands | ✅ Landlock, sandbox-exec | ✅ bubblewrap, Seatbelt | — | — | via Docker Sandboxes |
| Classified data kept on a local model | ✅ | — | — | — | — |
| Hash-chained, verifiable audit log | ✅ | — | — | — | — |
| Compliance report and RFC 3161 timestamps | ✅ | — | — | — | — |
| Signed organisation policy | ✅ minisign | managed settings | — | — | — |

“—” means not documented, to our knowledge, on 2026-10-24. Corrections are welcome: open an issue.

Sources: [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing), [Aider](https://aider.chat/), [OpenCode](https://opencode.ai/), [Mistral Vibe](https://mistral.ai/news/devstral-2-vibe-cli), [Docker Sandboxes for Vibe](https://docs.docker.com/guides/mistral-vibe-sandbox/).
