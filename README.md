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
