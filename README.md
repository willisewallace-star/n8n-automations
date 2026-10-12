# n8n-automations
AutomateLux Automatisations

Projet dédié aux workflows n8n avec Claude Code.

- `.mcp.json` : serveur [n8n-mcp](https://github.com/czlonkowski/n8n-mcp), lancé localement via `npx`.
- `.claude/settings.json` : plugin [n8n-skills](https://github.com/czlonkowski/n8n-skills) (skills + hooks).

## Configuration

Définir dans l'environnement (jamais dans un fichier du dépôt) :

- `N8N_API_URL` : URL de l'instance n8n, par ex. `https://mon-n8n.com`
- `N8N_API_KEY` : clé créée dans n8n, Settings → n8n API

Sans ces variables, le serveur fonctionne en mode documentation seulement.
