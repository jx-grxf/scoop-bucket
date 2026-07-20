# scoop-bucket

Scoop manifests for [jx-grxf](https://github.com/jx-grxf) tools.

```powershell
scoop bucket add jx-grxf https://github.com/jx-grxf/scoop-bucket
scoop install agent-presence
```

| Manifest | What |
|---|---|
| [`agent-presence`](bucket/agent-presence.json) | [Discord Rich Presence for Claude Code and Codex](https://github.com/jx-grxf/agent-presence) |

Manifests here are generated on release and pushed automatically. Edit them in the source
repository's `packaging/` templates, not here — a hand-edit is overwritten by the next
release.
