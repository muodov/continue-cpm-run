# continue-cpm-run

A link that opens Claude Code with `/continue-cpm-run <run ID>`, for comments in Asana, which won't link `claude://` URLs.

```
https://zok.pw/continue-cpm-run/?run=<GitHub Actions run ID>
https://zok.pw/continue-cpm-run/?run=<GitHub Actions run ID>&app=cli
```

The page sends the browser to `claude://code/new?repo=duckduckgo/tracker-radar-internal&q=/continue-cpm-run%20<run ID>`, which opens Claude Desktop. With `app=cli`, it sends it to `claude-cli://open?…` with the same parameters, which opens Claude Code in a terminal. It accepts only a numeric run ID, so it can't be used to open Claude Code with any other prompt.
