# continue-cpm-run

Links that open Claude Code with a CPM triage command, for Asana, which won't link `claude://` URLs.

```
https://zok.pw/continue-cpm-run/?run=<GitHub Actions run ID>
https://zok.pw/continue-cpm-run/?skill=merge-cpm-prs
```

`?run=` opens Claude Code with `/continue-cpm-run <run ID>`, and `?skill=merge-cpm-prs` with `/merge-cpm-prs`. The page sends the browser to `claude://code/new?repo=duckduckgo/tracker-radar-internal&q=<command>`, which opens Claude Desktop. Add `&app=cli` to send it to `claude-cli://open?…` with the same parameters instead, which opens Claude Code in a terminal.

The page accepts only these two commands, and only a numeric run ID, so it can't be used to open Claude Code with any other prompt.
