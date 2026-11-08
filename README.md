# Yuix-Networks Homebrew Tap

Recent Homebrew versions refuse to load formulae from a third-party tap until you trust
it, so trust the tap **before** installing:

```bash
brew tap yuix-networks/tap
brew trust yuix-networks/tap
brew install yuix-networks/tap/claude-orchestrator
```

| Formula | Description |
|---|---|
| [`claude-orchestrator`](https://github.com/Yuix-Networks/claude-orchestrator) | Run multiple Claude Desktop instances (one per account) on macOS and share projects and sessions between them |
