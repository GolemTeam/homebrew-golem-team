# homebrew-golem-team

Homebrew tap for [Golem](https://golem.team)'s open-source tools.

```sh
brew install golemteam/golem-team/golem-team-shield
```

That installs two programs from
[golem-team-shield](https://github.com/GolemTeam/golem-team-shield), on macOS
and Linux:

- **`golem-check`** reads the settings of Claude Code, Cursor, Codex, Gemini
  CLI, Devin and the VS Code family, and reports the ones that let an AI agent
  act without asking. It sends nothing anywhere.
- **`golem-exec`** runs every shell command Claude Code starts inside a kernel
  jail. Run `golem-exec install` once, then restart Claude Code.

`brew upgrade golem-team-shield` also updates the shim Claude Code runs.
`man golem-exec` and `man golem-check` cover every command and setting.

The cask is published from each release of golem-team-shield; don't edit it by
hand.
