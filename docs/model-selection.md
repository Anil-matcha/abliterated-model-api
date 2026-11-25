# Choosing a Abliterated Model route

This guide documents the three hosted routes grouped under Abliterated Model in Muapi's catalog. The base route accepts image input; the two Large routes are text-only and have 1M-token context windows.

## Compare the current routes

| Route | Context | Input | Input / output per 1M tokens | Maximum output | Selection note |
|---|---:|---|---:|---:|---|
| <code>abliterated-model</code> | 262K | Text + image | $2.00 / $6.00 | 32768 | Choose for text or image prompts when a 262K-token context window is sufficient. |
| <code>abliterated-model-large</code> | 1M | Text | $6.00 / $10.00 | 32768 | Choose for long text inputs when the Large route fits the budget and task. |
| <code>abliterated-model-large-v2</code> | 1M | Text | $6.00 / $10.00 | 32768 | Choose when you specifically want to evaluate Large V2; compare it with Large using a fixed prompt set. |

The table is a shortlist by documented interface, context, and price. It is not a quality ranking.

## A practical selection process

1. Start with input type. Use image_url only on a route whose Muapi schema lists image input.
2. Match the advertised context window to the total prompt size and leave room for the generated answer.
3. Set max_tokens to the output length your task needs; the cap varies by endpoint.
4. Estimate cost from expected input and output token counts using the separate rates.
5. For close choices, run the same prompts on each route and score them against your own criteria. This repository publishes no comparative benchmark scores.

## Model cards

- [Abliterated Model](models/abliterated-model.md) — Choose for text or image prompts when a 262K-token context window is sufficient.
- [Abliterated Model Large](models/abliterated-model-large.md) — Choose for long text inputs when the Large route fits the budget and task.
- [Abliterated Model Large V2](models/abliterated-model-large-v2.md) — Choose when you specifically want to evaluate Large V2; compare it with Large using a fixed prompt set.

Check the [Muapi live page](https://muapi.ai/abliterated-llm-api) for current availability and pricing.
