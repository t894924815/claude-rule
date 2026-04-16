# Claude Surge Rules

Standalone Surge ruleset project for Claude and Claude Code traffic.

## Files

- `dist/Claude.list`: default recommended ruleset
- `dist/Claude_Strict.list`: safer ruleset with lower false-positive risk
- `dist/Claude_Full.list`: broader ruleset with extra third-party telemetry and IP fallback

## Suggested Surge usage

```ini
[Rule]
RULE-SET,https://example.invalid/Claude.list,Claude
```

Replace the URL with one of the published links.
