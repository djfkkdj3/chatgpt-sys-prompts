# ChatGPT Prompt Snapshots

This repo archives ChatGPT prompt snapshots by date and model

The archive includes every prompt layer available for a snapshot:

- system prompts
- developer prompts
- personality prompts, when present
- partial captures, clearly marked

## Structure

```text
prompts/YYYY-MM-DD/model-name/
├── system.md
├── developer.md
├── personality.md
├── combined.md
└── metadata.md
```

Some snapshots use names like `developer-1.md`, `developer-2.md`, or `system.partial.md` when the capture has multiple layers or is incomplete.

## Current Snapshots

See [`INDEX.md`](INDEX.md) for the full list.

Included dates:

- 2026-03-27 — ChatGPT 5.4 Thinking Extended
- 2026-06-12 — ChatGPT 5.5 Thinking Extended
- 2026-07-06 — ChatGPT 5.3 Mini, partial
- 2026-07-07 — ChatGPT 5.5 Thinking
- 2026-07-09 — GPT-5.6 Sol (thinking: high)

## Completeness Labels

`Unknown` means the capture is preserved as-is, but completeness is not guaranteed.

`Partial` means the capture is visibly incomplete, truncated, or expanded from a partial output.

`Curated` means the capture intentionally omits identified audit-only or non-archival messages.

