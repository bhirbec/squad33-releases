# Squad33 releases

Squad33 is a kanban board on your own Mac for AI coding agents. Each ticket goes to Claude Code or Opencode, on the subscription you already pay for, in a git worktree of its own; a background worker implements it and opens a pull request. Pair your phone and run the board by voice from outside.

The app is closed source. This repository holds the release notes and the issue tracker.

## Download

[squad33-latest.dmg](https://squad33.ai/downloads/squad33-latest.dmg)

Apple Silicon Mac, macOS 11 or later. The app updates itself from [latest.json](https://squad33.ai/downloads/latest.json).

## What you need

- `claude` (Claude Code) or `opencode` on your `PATH`, signed in. Squad33 runs them on your own subscription; it has no key of its own.
- `gh` signed in, if you want tickets to end in pull requests.
- A Squad33 account. The app asks you to sign in on first launch.
- For voice: a phone, paired from the app. Speech is transcribed on the Mac.

## Reporting a bug

[Open an issue](https://github.com/bhirbec/squad33-releases/issues/new/choose). The template asks for the version, the agent, what you said and what happened. **Share log**, in the app under Admin, Log, uploads your log and shows a key to paste in the report.

Or write to hey@squad33.ai.

## Links

- [squad33.ai](https://squad33.ai)
- [Blog](https://squad33.ai/blog)
- [Terms](https://squad33.ai/terms)
