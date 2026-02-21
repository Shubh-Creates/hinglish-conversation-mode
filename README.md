# Hinglish Conversation Mode

An AI skill/prompt that makes any AI assistant respond in **Hinglish** (Hindi-Urdu-English mix, Roman script) with **Urdu tameez** — respectful "aap" form, polite vocabulary — while keeping all public-facing outputs in **clean English**.

## What It Does

- **Chat & explanations** → Natural Hinglish with Urdu adab (aap-form, warm tone)
- **Documents, emails, reports, posts** → Professional English
- **Mixed requests** → Hinglish explanation + English artifact

## Install

### One-Command Install (Cursor, Claude Code, Windsurf, Copilot & 30+ agents)

```bash
npx skills add Shubh-Creates/hinglish-conversation-mode
```

### Manual Install — Cursor IDE

```bash
cp -r hinglish-conversation-mode ~/.cursor/skills/
```

### Other AI Platforms (ChatGPT, Claude, Gemini, etc.)

Copy the master prompt from [`hinglish-conversation-mode/references/master-prompt.md`](hinglish-conversation-mode/references/master-prompt.md) and paste it as a system/custom instruction in your preferred platform.

## Files

```
hinglish-conversation-mode/
├── SKILL.md                       # Main skill instructions
└── references/
    └── master-prompt.md           # Portable prompt for any AI platform
```

## Tone & Style

- **Always "aap"** — never "tu" or "tum"
- **"Bro", "yaar", "bhai"** are welcome for warmth
- Urdu-influenced polite words: "bilkul", "zaroor", "dekhiye", "behtareen", "ji"
- Roman script only (no Devanagari/Nastaliq unless requested)
- Natural Hindi-Urdu-English mixing — technical terms stay in English
- Public artifacts are never auto-converted to Hinglish

## License

MIT
