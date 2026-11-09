# claude-skills

Koleksi skill Claude (format `SKILL.md`) milik Faisal Helmy, disimpan di `.agents/skills/<nama-skill>/`.

**Total: 128 skill.** Semua berlisensi Apache-2.0; salinan lisensi ada di setiap folder skill.

## Cara pakai

- **Claude Code**: salin folder skill ke `~/.claude/skills/` (global) atau `.claude/skills/` (per proyek).
- **claude.ai / Cowork**: zip satu folder skill lalu upload lewat *Settings → Capabilities → Skills*.

Catatan: beberapa skill (sales, marketing, finance, dll.) dirancang untuk bekerja dengan connector (CRM, email, kalender). Tanpa connector, skill tetap bisa dipakai dengan data yang Anda upload.

## Daftar skill

| Skill | Group | Source | License |
|---|---|---|---|
| `docx` | anthropic-skills | Anthropic | Apache-2.0 |
| `pdf` | anthropic-skills | Anthropic | Apache-2.0 |
| `pptx` | anthropic-skills | Anthropic | Apache-2.0 |
| `skill-creator` | anthropic-skills | Anthropic | Apache-2.0 |
| `xlsx` | anthropic-skills | Anthropic | Apache-2.0 |
| `cowork-plugin-customizer` | cowork-plugin-management | Anthropic — cowork-plugin-management plugin | Apache-2.0 |
| `create-cowork-plugin` | cowork-plugin-management | Anthropic — cowork-plugin-management plugin | Apache-2.0 |
| `analyze` | data | Anthropic — data plugin | Apache-2.0 |
| `build-dashboard` | data | Anthropic — data plugin | Apache-2.0 |
| `create-viz` | data | Anthropic — data plugin | Apache-2.0 |
| `data-context-extractor` | data | Anthropic — data plugin | Apache-2.0 |
| `data-visualization` | data | Anthropic — data plugin | Apache-2.0 |
| `explore-data` | data | Anthropic — data plugin | Apache-2.0 |
| `sql-queries` | data | Anthropic — data plugin | Apache-2.0 |
| `statistical-analysis` | data | Anthropic — data plugin | Apache-2.0 |
| `validate-data` | data | Anthropic — data plugin | Apache-2.0 |
| `write-query` | data | Anthropic — data plugin | Apache-2.0 |
| `accessibility-review` | design | Anthropic — design plugin | Apache-2.0 |
| `design-critique` | design | Anthropic — design plugin | Apache-2.0 |
| `design-handoff` | design | Anthropic — design plugin | Apache-2.0 |
| `design-system` | design | Anthropic — design plugin | Apache-2.0 |
| `research-synthesis` | design | Anthropic — design plugin | Apache-2.0 |
| `user-research` | design | Anthropic — design plugin | Apache-2.0 |
| `ux-copy` | design | Anthropic — design plugin | Apache-2.0 |
| `architecture` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `code-review` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `debug` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `deploy-checklist` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `documentation` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `incident-response` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `standup` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `system-design` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `tech-debt` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `testing-strategy` | engineering | Anthropic — engineering plugin | Apache-2.0 |
| `audit-support` | finance | Anthropic — finance plugin | Apache-2.0 |
| `close-management` | finance | Anthropic — finance plugin | Apache-2.0 |
| `financial-statements` | finance | Anthropic — finance plugin | Apache-2.0 |
| `journal-entry-prep` | finance | Anthropic — finance plugin | Apache-2.0 |
| `journal-entry` | finance | Anthropic — finance plugin | Apache-2.0 |
| `reconciliation` | finance | Anthropic — finance plugin | Apache-2.0 |
| `sox-testing` | finance | Anthropic — finance plugin | Apache-2.0 |
| `variance-analysis` | finance | Anthropic — finance plugin | Apache-2.0 |
| `brand-review` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `campaign-plan` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `competitive-brief` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `content-creation` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `draft-content` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `email-sequence` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `performance-report` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `seo-audit` | marketing | Anthropic — marketing plugin | Apache-2.0 |
| `memory-management` | productivity | Anthropic — productivity plugin | Apache-2.0 |
| `start` | productivity | Anthropic — productivity plugin | Apache-2.0 |
| `task-management` | productivity | Anthropic — productivity plugin | Apache-2.0 |
| `update` | productivity | Anthropic — productivity plugin | Apache-2.0 |
| `account-context` | sales | Anthropic — sales plugin | Apache-2.0 |
| `account-plan` | sales | Anthropic — sales plugin | Apache-2.0 |
| `account-research` | sales | Anthropic — sales plugin | Apache-2.0 |
| `account-tiering` | sales | Anthropic — sales plugin | Apache-2.0 |
| `call-prep` | sales | Anthropic — sales plugin | Apache-2.0 |
| `call-summary` | sales | Anthropic — sales plugin | Apache-2.0 |
| `close-plan` | sales | Anthropic — sales plugin | Apache-2.0 |
| `competitive-intelligence` | sales | Anthropic — sales plugin | Apache-2.0 |
| `create-an-asset` | sales | Anthropic — sales plugin | Apache-2.0 |
| `crm-hygiene-check` | sales | Anthropic — sales plugin | Apache-2.0 |
| `customer-health` | sales | Anthropic — sales plugin | Apache-2.0 |
| `customer-voice` | sales | Anthropic — sales plugin | Apache-2.0 |
| `daily-briefing` | sales | Anthropic — sales plugin | Apache-2.0 |
| `deal-advance-gap` | sales | Anthropic — sales plugin | Apache-2.0 |
| `deal-review` | sales | Anthropic — sales plugin | Apache-2.0 |
| `deal-signals` | sales | Anthropic — sales plugin | Apache-2.0 |
| `deal-slip-scenario` | sales | Anthropic — sales plugin | Apache-2.0 |
| `draft-outreach` | sales | Anthropic — sales plugin | Apache-2.0 |
| `end-of-day` | sales | Anthropic — sales plugin | Apache-2.0 |
| `expansion-whitespace` | sales | Anthropic — sales plugin | Apache-2.0 |
| `forecast` | sales | Anthropic — sales plugin | Apache-2.0 |
| `handle-objection` | sales | Anthropic — sales plugin | Apache-2.0 |
| `inbox-sweep` | sales | Anthropic — sales plugin | Apache-2.0 |
| `lead-triage` | sales | Anthropic — sales plugin | Apache-2.0 |
| `log-activity` | sales | Anthropic — sales plugin | Apache-2.0 |
| `pipeline-review` | sales | Anthropic — sales plugin | Apache-2.0 |
| `renewal-radar` | sales | Anthropic — sales plugin | Apache-2.0 |
| `rep-context` | sales | Anthropic — sales plugin | Apache-2.0 |
| `route-lead` | sales | Anthropic — sales plugin | Apache-2.0 |
| `schedule-meeting` | sales | Anthropic — sales plugin | Apache-2.0 |
| `setup` | sales | Anthropic — sales plugin | Apache-2.0 |
| `stakeholder-map` | sales | Anthropic — sales plugin | Apache-2.0 |
| `team-pipeline` | sales | Anthropic — sales plugin | Apache-2.0 |
| `update-opportunity` | sales | Anthropic — sales plugin | Apache-2.0 |
| `weekly-wrap` | sales | Anthropic — sales plugin | Apache-2.0 |
| `win-loss-review` | sales | Anthropic — sales plugin | Apache-2.0 |
| `ios-design` | uizze | Uizze | Apache-2.0 |
| `ui-taste` | uizze | Uizze | Apache-2.0 |
| `access-protected-vercel-deployment` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `ai-gateway` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `ai-sdk` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `auth` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `bootstrap` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `build-agents` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `cdn-caching` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `chat-sdk` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `create-a-backend` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `deployments-cicd` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `env-vars` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `eve` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `flags-sdk` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `knowledge-update` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `marketplace` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `microfrontends` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `next-cache-components` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `next-forge` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `next-upgrade` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `nextjs` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `react-best-practices` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `routing-middleware` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `runtime-cache` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `shadcn` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `turbopack` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-agent` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-cli` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-connect` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-firewall` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-functions` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-sandbox` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-services` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `vercel-storage` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `verification` | vercel | Vercel — vercel plugin | Apache-2.0 |
| `web-design-guidelines` | vercel | vercel-labs/agent-skills | Apache-2.0 |
| `workflow` | vercel | Vercel — vercel plugin | Apache-2.0 |
