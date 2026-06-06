# Hermes bots

Deploys every agent as a **Hermes bot** — a per-bot config (`bot.yaml`) plus the persona as a separate `system.md` system prompt. Each agent becomes a bot your Hermes gateway can run (WhatsApp, Telegram, Slack, etc.).

## Install

```bash
./scripts/convert.sh --tool hermes             # generate integrations/hermes/<slug>/{bot.yaml,system.md}
./scripts/install.sh --tool hermes             # copy to ~/.hermes/bots/<slug>/
```

If your Hermes loads bots from a different path, set `HERMES_BOTS_DIR`:

```bash
HERMES_BOTS_DIR=~/.hermes/agents ./scripts/install.sh --tool hermes
```

After installing, reload the gateway so it picks up the new bots.

## Format

`~/.hermes/bots/<slug>/bot.yaml`:

```yaml
bot:
  name: <slug>
  display_name: '<Agent Name>'
  description: '<what it does>'
  enabled: true
  model: default                 # resolved by your Hermes model-routing
  system_prompt_path: ./system.md
  gateway:
    platforms: []                # e.g. [whatsapp, telegram] — where this bot answers
  skills: []                     # optional ~/.hermes/skills this bot may call
  metadata: { emoji, vibe, source, date_added }
```

`system.md` holds the full persona (the agent body) so the long prompt never has to be escaped into YAML.

## Notes
- Field names mirror common Hermes bot configs — **adjust them to your Hermes version** if they differ; the `system.md` content is portable regardless.
- Bind each bot to a platform by filling in `gateway.platforms`, and attach any `~/.hermes/skills` it should be able to call under `skills`.
- Generated files are git-ignored; re-run `convert.sh` after editing any agent.
