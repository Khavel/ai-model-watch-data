# AI Model Watch — open dataset

An open, MIT-licensed, **daily-updated** dataset of AI/LLM models: prices (USD per 1M tokens),
context windows, modality, lifecycle status, and **deprecation/retirement dates** — across all major
providers. Compiled from official provider documentation.

- **`models.json`** — full structured catalog.
- **`models.csv`** — flat table (spreadsheet/pandas friendly).

Powered by **[AI Model Watch](https://aimodelwatch.dev)** — live site, comparisons, a cost calculator,
a deprecation watch, and free email alerts when anything changes.

## Use it
```bash
curl -L https://raw.githubusercontent.com/Khavel/ai-model-watch-data/main/models.json
```
Free to use in your apps, articles, and agents. Attribution appreciated: link to https://aimodelwatch.dev.

> Data provided as-is; verify against official provider pages before relying on a price for billing.
