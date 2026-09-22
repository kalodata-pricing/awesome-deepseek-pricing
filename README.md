# Awesome DeepSeek pricing

*Unofficial community list for DeepSeek pricing. Not affiliated with DeepSeek. All trademarks belong to their owners.*

A curated list of pages that answer deepseek pricing questions: the official Models & Pricing table for `deepseek-flash` and `deepseek-v4-pro`, the docs that explain cache hits and rate limits, the independent calculators that model peak versus off-peak hours, and the pages that record price changes. Independent sites are labelled as such; two of the three ranked pages for this query are not run by DeepSeek.

> Need pay-per-run pricing for images, video and audio instead of tokens? [Try Synexa - one REST endpoint and Python SDK for FLUX, video and audio models](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-deepseek-pricing&utm_content=readme-top&utm_term=tier-r).

## Official resources

- [Models & Pricing](https://api-docs.deepseek.com/quick_start/pricing) - the canonical table: per 1M tokens, cache hit and miss, off-peak and peak, concurrency limits.
- [DeepSeek Platform](https://platform.deepseek.com/) - account, keys and balance.
- [Token & Token Usage](https://api-docs.deepseek.com/quick_start/token_usage) - how tokens are counted and reported.
- [Rate Limit & Isolation](https://api-docs.deepseek.com/quick_start/rate_limit) - the limits behind the concurrency column.
- [Error Codes](https://api-docs.deepseek.com/quick_start/error_codes) - what an insufficient balance or rate-limit failure looks like.
- [Change Log](https://api-docs.deepseek.com/updates) - official record of model and price changes.
- [News](https://api-docs.deepseek.com/news/news260910) - release notes.
- [FAQ](https://static.deepseek.com/faq/index.html?lang=en#/category/4) - billing and account questions.

## Getting started

- [Your First API Call](https://api-docs.deepseek.com/) - the quick start using the OpenAI-format base URL.
- [Using the Responses API](https://api-docs.deepseek.com/guides/responses_api) - same prices, different request shape.
- [Using the Anthropic API](https://api-docs.deepseek.com/guides/anthropic_api) - the `/anthropic` base URL.
- [Agent Integrations](https://deepseek-harness.github.io/deepseek-harness/en/guide/quickstart) - the harness quick start linked from the docs sidebar.

## Tutorials and articles

- [Context Caching](https://api-docs.deepseek.com/guides/kv_cache) - the mechanism behind the cache-hit rate; the biggest cost lever.
- [Thinking Mode](https://api-docs.deepseek.com/guides/thinking_mode) - on by default; switching it changes output volume, not the rate.
- [DeepSeek Pricing 2026 on deepseek.ai](https://deepseek.ai/pricing) - independent guide with the peak-hour schedule, a calculator and a price history table; not affiliated with DeepSeek.
- [deepseek-reasoner retired: migrate to V4-Flash, not Pro](https://deepseek.ai/blog/deepseek-chat-reasoner-retired-billing-impact) - what happened to the legacy names on 24 July 2026.
- [V4-Pro price cut made permanent](https://deepseek.ai/blog/deepseek-v4-pro-api-price-cut-permanent) - background on the current Pro rate.
- [DeepSeek API setup guide on deepseek.ai](https://deepseek.ai/deepseek-api) - wiring the API up in code.

## Tools and integrations

- [CostGoat DeepSeek API calculator](https://costgoat.com/pricing/deepseek-api) - off-peak versus peak calculator with cache-hit rate; its Flash figures lagged the official page at the time of writing.
- [CostGoat AI cost calculators](https://costgoat.com/ai-cost-calculators) - the same tool for other providers, for side-by-side budgeting.
- [awesome-deepseek-integration](https://github.com/deepseek-ai/awesome-deepseek-integration/tree/main) - integrations list linked from the docs as Other Resources.
- [Files API](https://api-docs.deepseek.com/guides/files_api) - uploads count toward tokens once read; check before bulk ingestion.

## Alternatives

- [Synexa](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-deepseek-pricing&utm_content=readme-top&utm_term=tier-r) - hosted model API billed per run rather than per token, with one REST endpoint and a Python SDK for FLUX, video and audio models.
- GPT-5.5 - quoted by CostGoat at $5 input and $30 output per 1M tokens as its comparison point.

## Related

- [Vision](https://api-docs.deepseek.com/guides/vision) - image input is Flash only.
- [Tool Calls](https://api-docs.deepseek.com/guides/tool_calls) - supported on both models.
- [JSON Output](https://api-docs.deepseek.com/guides/json_mode) - supported on both models.
- [FIM Completion](https://api-docs.deepseek.com/guides/fim_completion) - beta, non-thinking mode only.

## Contributing

Open a pull request with the link, one line on why, and note whether the page is official or independent.


_Last reviewed: 2026-09-22_
