# ferronis/tap

Homebrew formulae for ferronis projects.

## Save Me

[Save Me](https://github.com/ferronis/save-me) pulls your saved posts from Threads, Instagram, Bluesky, X, and Reddit into one local feed, and lets Claude sort them and suggest what to do next.

```bash
brew install --HEAD ferronis/tap/save-me
save-me setup                  # finds Claude Code and prints your ingest token
brew services start save-me    # runs Save Me now and every time you log in
```

Then open http://localhost:3080 and install the browser extension. See the [Save Me README](https://github.com/ferronis/save-me#install) for the full steps.

The formula's source of truth is [`packaging/homebrew/save-me.rb`](https://github.com/ferronis/save-me/blob/main/packaging/homebrew/save-me.rb) in the Save Me repo.
