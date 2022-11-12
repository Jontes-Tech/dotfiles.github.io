---
description: The Tmux aliases are a collection of aliases that allow you to interact with the `tmux` command. Tmux is a tool which allows you to run multiple terminal sessions in a single window.
lang: en-GB
metaTitle: The Tmux aliases - Dotfiles (UK)
permalink: /aliases/tmux/

meta:
  - name: keywords
    content: aliases, tmux, linux, macos, shell, terminal, windows
  - name: twitter:card
    content: The Tmux aliases are a collection of aliases that allow you to interact with the `tmux` command. Tmux is a tool which allows you to run multiple terminal sessions in a single window.
  - name: twitter:description
    content: The Tmux aliases are a collection of aliases that allow you to interact with the `tmux` command. Tmux is a tool which allows you to run multiple terminal sessions in a single window.
  - name: twitter:title
    content: The Tmux aliases - Dotfiles (UK)
  - name: og:title
    content: The Tmux aliases - Dotfiles (UK)
  - name: og:description
    content: The Tmux aliases are a collection of aliases that allow you to interact with the `tmux` command. Tmux is a tool which allows you to run multiple terminal sessions in a single window.
  - name: og:image:alt
    content: Dotfiles - Simply designed to fit your shell life
  - name: og:locale
    content: en_GB
---

# Tmux aliases

This `tmux.aliases.zsh` file creates helpful shortcut aliases for many
commonly used [tmux](https://github.com/tmux/tmux/wiki) commands.

The Tmux aliases are a collection of aliases that allow you to interact with the
`tmux` command. Tmux is a tool which allows you to run multiple terminal
sessions in a single window.

## Tmux

[Tmux](https://github.com/tmux/tmux/wiki) is a terminal multiplexer. It lets you
switch easily between several programs in one terminal, detach them (they keep
running in the background) and reattach them to a different terminal.

| Alias | Command | Description |
| ----- | ----- | ----- |
| tm |`tmux` | Start tmux. |
| tma |`tmux attach-session` | Attach to a tmux session. |
| tmat |`tmux attach-session -t` | Attach to a tmux session with name. |
| tmks |`tmux kill-session -a` | Kill all tmux sessions. |
| tml |`tmux list-sessions` | List tmux sessions. |
| tmn |`tmux new-session` | Start a new tmux session. |
| tmns |`tmux new -s` | Start a new tmux session with name. |
| tms |`tmux new-session -s` | Start a new tmux session. |
