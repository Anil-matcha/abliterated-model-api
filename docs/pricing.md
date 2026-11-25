# Pricing

The figures below are Muapi catalog rates per million tokens, checked on 2026-11-25. Input and output rates can differ. These values are a dated snapshot; verify the live Muapi page before budgeting.

| Model | Input / 1M | Output / 1M | Context | Input type |
|---|---:|---:|---:|---|
| <code>abliterated-model</code> | $2.00 | $6.00 | 262K | Text + image |
| <code>abliterated-model-large</code> | $6.00 | $10.00 | 1M | Text |
| <code>abliterated-model-large-v2</code> | $6.00 | $10.00 | 1M | Text |

## Estimate a request

A rough estimate is:

```text
estimated cost = (input tokens × input rate + output tokens × output rate) ÷ 1,000,000
```

Actual charges depend on usage and Muapi's current billing rules. Check the response usage or cost fields and your Muapi dashboard for account totals.

## Price changes

Model availability, context limits, fields, and rates can change. Verify the live [Muapi model page](https://muapi.ai/abliterated-llm-api) or the [Muapi catalog](https://muapi.ai/models).
