# Serenity Alpha Skill

A Codex skill that translates market news into testable alpha hypotheses using a "news -> demand -> financial statements -> small-cap elasticity -> validation path" framework.

## 直接使用托管版

如果你觉得本地安装、配置 Codex skill 或维护环境不方便，也可以订阅 [@iamai_omni](https://x.com/iamai_omni/creator-subscriptions/subscribe)，然后访问 [app.k2ai.dev](https://app.k2ai.dev) 直接使用托管版。订阅版不需要你自己搭建，并且会附赠许多其他功能，适合想快速上手、持续使用 Serenity 体系的用户。也可以扫码直接打开订阅页：

<img src="docs/assets/iamai-omni-subscribe-qr.png" alt="Subscribe to @iamai_omni QR code" width="220">

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
