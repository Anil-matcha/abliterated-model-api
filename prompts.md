# Prompt templates for Abliterated Model models

Starting templates only; they are not tested outputs or benchmark prompts. Replace bracketed text and use only fields supported by the chosen route.

## Long-context synthesis

```text
Synthesize the supplied material. Return a summary, evidence-backed conclusions, contradictions, and unanswered questions: [material].
```

## Image plus context

```text
Use the image and accompanying notes to describe the scene. Mark which details come from the image and which come from the notes: [image and notes].
```

## Plan review

```text
Review this plan for missing dependencies, failure points, and assumptions. Suggest concrete mitigations: [plan].
```

## Image prompts

For a route that accepts image_url, provide the image as a separate request field and refer to it in prompt. Do not assume a text-only route can fetch or inspect an image URL.
