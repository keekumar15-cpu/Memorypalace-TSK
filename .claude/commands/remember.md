---
description: Save an insight to my Memory Palace (decision, mistake/bug, win, or prompt-pattern)
allowed-tools: Bash
---

Save one memory to the Memory Palace.

If I typed text after the command, use it. Otherwise summarise the single most useful decision, bug-fix, win or prompt-pattern from our recent conversation in one or two sentences.

Pick a type from: decision | mistake | win | prompt-pattern | convention | gotcha.
NEVER include API keys, tokens, passwords, or customer PII (names, emails).

Then run (replace TYPE and INSIGHT):

```bash
python3 "$(git rev-parse --show-toplevel)/.claude/memory-palace/mp.py" remember "TYPE: INSIGHT"
```

Then tell me exactly what you saved.
