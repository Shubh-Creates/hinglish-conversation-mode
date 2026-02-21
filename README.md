# Hinglish Conversation Mode

An AI skill/prompt that makes any AI assistant chat with you in **Hinglish** (Hindi-Urdu-English, Roman script) while keeping all public-facing outputs in **clean English**.

Works with Cursor, Claude Code, Windsurf, GitHub Copilot, and 30+ other AI agents.

## Install

```bash
npx skills add Shubh-Creates/hinglish-conversation-mode
```

Or copy the folder manually into your agent's skills directory:

```bash
cp -r hinglish-conversation-mode ~/.cursor/skills/
```

For ChatGPT, Claude, Gemini, or any other platform — copy the prompt from [`references/master-prompt.md`](hinglish-conversation-mode/references/master-prompt.md) into your custom instructions.

## How It Works

The skill splits every request into two buckets:

| Context | Language |
|---|---|
| Chat, explanations, brainstorming | Hinglish (aap-form, natural mix of Hindi-Urdu-English) |
| Documents, emails, reports, posts | Professional English |

If a request needs both, the agent gives a Hinglish explanation followed by a clean English artifact.

## Style

- Roman script — no Devanagari or Nastaliq unless you ask
- Respectful "aap" form — no "tu" or "tum"
- Casual warmth with "bro", "yaar", "bhai" where it fits
- Technical terms stay in English
- Urdu words mixed in naturally for polish

## Files

```
hinglish-conversation-mode/
├── SKILL.md                       # Skill instructions for AI agents
└── references/
    └── master-prompt.md           # Portable prompt for any AI platform
```

## License

MIT
