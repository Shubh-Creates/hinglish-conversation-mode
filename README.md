# Hinglish Conversation Mode

An AI skill/prompt that makes any AI assistant respond in **Hinglish** (Hindi-English mix, Roman script) for casual conversation while keeping all public-facing outputs in **clean English**.

## What It Does

- **Chat & explanations** → Natural Hinglish
- **Documents, emails, reports, posts** → Professional English
- **Mixed requests** → Hinglish explanation + English artifact

## Quick Setup

### Cursor IDE

Copy the skill folder into your personal skills directory:

```bash
cp -r hinglish-conversation-mode ~/.cursor/skills/
```

The agent will automatically pick it up across all projects.

### Other AI Platforms (ChatGPT, Claude, etc.)

Copy the master prompt from [`hinglish-conversation-mode/references/master-prompt.md`](hinglish-conversation-mode/references/master-prompt.md) and paste it as a system/custom instruction in your preferred platform.

## Files

```
hinglish-conversation-mode/
├── SKILL.md                       # Main skill instructions
└── references/
    └── master-prompt.md           # Portable prompt for any AI platform
```

## Style Rules

- Roman script only (no Devanagari unless requested)
- Natural Hindi-English mixing — technical terms stay in English
- Clear and concise tone, no heavy slang
- Public artifacts are never auto-converted to Hinglish

## License

MIT
