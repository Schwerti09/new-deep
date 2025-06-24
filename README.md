# AUTOMIND - AI Agency-in-a-Box
**Ein-Klick-Deployment:**  
`./deploy/god_mode.sh`

## Systemanforderungen
- Docker
- Node.js 18+
- Deno Runtime

## Umgebungsvariablen
.env-Beispiel:
OPENAI_API_KEY=sk_pro_...
STRIPE_APOCALYPSE_KEY=sk_live_...
ANTHROPIC_API_KEY=claude_...
QUANTUM_ENTROPY=0.98# new-deep

2. README.md
```markdown
# AUTOMIND - AI Agency-in-a-Box
## Starten ohne Docker:
```bash
cd frontend && npm install && npm run dev
cd backend && deno run --allow-net main.ts
