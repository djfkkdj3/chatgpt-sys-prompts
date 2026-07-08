# Contributing

Add prompt snapshots in the dated folder format:

```text
prompts/YYYY-MM-DD/model-name/
```

Use the exact model name from the capture. Keep prompt layers separate. If a capture is incomplete, name the file with `.partial.md` and mark the metadata as `Partial`.

Before opening a PR, check that:

- the date is present
- the model name is present
- each prompt layer is separate
- `combined.md` is only a convenience copy
- `metadata.md` says whether the capture is complete, partial, or unknown

Do not polish the prompt text. Archive it.
