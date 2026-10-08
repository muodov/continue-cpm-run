# continue-cpm-run

A link that opens Claude Code with `/continue-cpm-run <run ID>`, for comments in Asana, which won't link `claude://` URLs.

```
https://zok.pw/continue-cpm-run/?run=<GitHub Actions run ID>
```

The page sends the browser to `claude://code/new?q=/continue-cpm-run%20<run ID>`. It accepts only a numeric run ID, so it can't be used to open Claude Code with any other prompt.
