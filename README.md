# lobrzut

IT & cybersec admin · homelab · self-hosted AI

## Pomnia

Local-first **memory layer for MCP agents**. Not an agentic wrapper — vault + RAG + MCP that agents actually use.

- Site: [pomnia.ai](https://pomnia.ai)
- Product: [lobrzut/pomnia](https://github.com/lobrzut/pomnia) (AGPL-3.0-only)
- Landing: [lobrzut/pomnia-landing](https://github.com/lobrzut/pomnia-landing)

**Install**

- Windows: download from [pomnia.ai](https://pomnia.ai)
- Linux server: `curl -fsSL https://pomnia.ai/install.sh | sh`

**Honesty:** archive blobs are AES-encrypted; the searchable index stays plaintext on disk. Protect the machine / folder.

PL: warstwa pamięci pod MCP — lokalnie, bez chmury jako wymogu.

---

## NetDash

Homelab services dashboard — discovery, health, Docker monitoring. Strong self-hosted companion to the rest of the stack.

- Repo: [lobrzut/netdash](https://github.com/lobrzut/netdash)
- Releases: [netdash/releases](https://github.com/lobrzut/netdash/releases)
- Default port: `:18787`

---

## Also

- **[ai-studio](https://github.com/lobrzut/ai-studio)** — ComfyUI + ACE-Step (`:7880`)

---

## Sunset: Brain AI Hub / Reliqua

**Superseded by Pomnia.** The public [brain](https://github.com/lobrzut/brain) repo (old Brain AI Hub, dashboard `:7860`) remains for history and anyone still running it locally. Archiving on GitHub ≠ stopping a homelab service.

Older write-up: [dev.to](https://dev.to/lobrzut/self-hosted-second-brain-with-mcp-59d4)
