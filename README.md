<p align="center">
  <img src="https://proxystacks.com/icon.svg" width="64" height="64" alt="ProxyStacks Relay logo" />
</p>

<h1 align="center">ProxyStacks Lab</h1>

<p align="center">
  Engineering account behind <a href="https://proxystacks.com/en"><b>ProxyStacks Relay</b></a> —
  one OpenAI-compatible API for DeepSeek, GLM &amp; Kimi on a single prepaid balance.<br/>
  Pay-as-you-go. No subscriptions.
</p>

<p align="center">
  <a href="https://proxystacks.com/en/compare"><img src="https://img.shields.io/badge/pricing-up%20to%2070%25%20below%20official%20list-ff7a1a?style=flat-square" alt="Pricing" /></a>
  <a href="https://proxystacks.com/en"><img src="https://img.shields.io/badge/website-proxystacks.com-0a0a0a?style=flat-square" alt="Website" /></a>
  <a href="https://proxystacks.com/en/docs"><img src="https://img.shields.io/badge/docs-get%20started-2ea043?style=flat-square" alt="Docs" /></a>
  <a href="https://proxystacks.com/en/status"><img src="https://img.shields.io/badge/status-live%20page-57606a?style=flat-square" alt="Status" /></a>
</p>

---

## What Relay is

A multi-model AI API gateway for developers. One `base_url`, one USD balance, per-token
billing at published rates — works with the OpenAI SDK, Anthropic-compatible clients,
Claude Code, Codex and OpenCode.

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://proxystacks.com/v1",
    api_key="YOUR_RELAY_API_KEY",
)

resp = client.chat.completions.create(
    model="deepseek-v4.1-flash",
    messages=[{"role": "user", "content": "Hello!"}],
)
```

Compatible endpoints: `/v1/chat/completions` · `/v1/responses` · `/anthropic/v1/messages`

## Below official list price — always, and even lower off-peak

Per-token billing from a prepaid USD balance. Every model is priced below the
provider's official list, and `deepseek-v4.1-flash` gets an additional **off-peak
rate (~70% below official)** during weekends and weekday off-hours.

| Model | Official list<br/>in / out | Relay | You save |
|---|---|---|---|
| `deepseek-v4.1-flash` | $0.30 / $1.20 | $0.18 / $0.74 | **40% / 38%** |
| `deepseek-v4.1-flash` ⚡ off-peak | $0.30 / $1.20 | **$0.0895 / $0.37** | **~70% / 69%** |
| `glm-5.3` | $1.20 / $4.40 | $0.78 / $2.86 | **35%** |
| `glm-5.3-flash` | $0.15 / $0.50 | $0.098 / $0.33 | **35% / 34%** |
| `kimi-k3.1-pro` | $2.00 / $10.00 | $1.60 / $8.00 | **20%** |

<sub>USD per 1M tokens. Off-peak windows (Asia/Shanghai): weekends all day;
weekdays 00:00–09:00, 12:00–14:00, 18:00–24:00. Full rates incl. cache
pricing → [compare page](https://proxystacks.com/en/compare) ·
[live rates JSON](https://proxystacks.com/public/model-rates)</sub>

## What this account does

We contribute provider, model and public pricing data back to the open-source LLM
ecosystem — the same data that powers [proxystacks.com/public/model-rates](https://proxystacks.com/public/model-rates):

- [`anomalyco/models.dev`](https://github.com/anomalyco/models.dev) — provider & model metadata
- [`BerriAI/litellm`](https://github.com/BerriAI/litellm) — provider registry entries
- [`charmbracelet/catwalk`](https://github.com/charmbracelet/catwalk) — provider configs

## Links

| | |
|---|---|
| 🌐 Website | [proxystacks.com](https://proxystacks.com/en) |
| 📖 Docs | [proxystacks.com/en/docs](https://proxystacks.com/en/docs) |
| 💲 Pricing | [proxystacks.com/en/pricing](https://proxystacks.com/en/pricing) |
| 🧠 Models | [proxystacks.com/en/models](https://proxystacks.com/en/models) |
| ⚖️ Compare | [proxystacks.com/en/compare](https://proxystacks.com/en/compare) |
| ✅ Status | [proxystacks.com/en/status](https://proxystacks.com/en/status) |
| ✉️ Support | support@proxystacks.com |

<p align="center">
  中文站：<a href="https://proxystacks.com/zh-CN">proxystacks.com/zh-CN</a>
</p>
