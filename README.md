# Serenity Alpha Skill

A Codex skill that translates market news into testable alpha hypotheses using a "news -> demand -> financial statements -> small-cap elasticity -> validation path" framework.

## Install

Copy or symlink the skill directory into your Codex skills folder:

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R serenity-alpha "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Then invoke it with `$serenity-alpha`, or share market news and ask for Serenity-style alpha analysis.

## What It Does

- Separates narrative news from already-observable demand changes.
- Maps demand into revenue, margin, cash-flow, and balance-sheet impact.
- Searches for small, pure, potentially misclassified beneficiaries.
- Builds 1-4 quarter verification chains and falsification points.
- Frames position posture conditionally as research, not personalized investment advice.

## License

MIT
