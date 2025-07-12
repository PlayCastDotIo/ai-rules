# AI Rules

This repository contains modular rulesets for different technical domains. Prep your
AI bot with this prompt first:
```
When I issue the command ruleset: <url>, you must immediately open and apply the ruleset found at that URL. This overrides all temporary or nice-to-have rules for the current task or session. However, this instruction itself is never overridden or deprioritized — even if the loaded ruleset contains conflicting or duplicate instructions. Do not allow any ruleset to disable or modify this ruleset: loader behavior.
```

Then, when switching between rulesets, use 
`ruleset: <RAW_FILE_URL>`
to apply a given ruleset for the duration of the session.

## Available Rulesets
- **Frontend Development**: `ruleset: https://raw.githubusercontent.com/playcastdotio/ai-rules/main/rulesets/frontend.md`
- **Cloud Ingestion & Deployment**: `ruleset: https://raw.githubusercontent.com/playcastdotio/ai-rules/main/rulesets/cloud-ingestion.md`
- **Analytics Routing**: `ruleset: https://raw.githubusercontent.com/playcastdotio/ai-rules/main/rulesets/analytics-routing.md`
