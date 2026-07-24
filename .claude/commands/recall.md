---
description: Search my Memory Palace for relevant past decisions, bugs, wins and prompt-patterns
allowed-tools: Bash
---

Search the Memory Palace, then show me the matches.

Run this bash command (quote the query exactly):

```bash
python3 "$(git rev-parse --show-toplevel)/.claude/memory-palace/mp.py" recall "$ARGUMENTS" --limit 8
```

Then summarise which results are relevant to what we are doing now.
