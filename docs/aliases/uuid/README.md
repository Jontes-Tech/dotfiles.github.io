---
description: The UUID aliases create helpful shortcut aliases for the `uuidgen` command. The uuidgen command generates a Universally Unique IDentifier (UUID), a 128-bit value guaranteed to be unique over both space and time.
lang: en-GB
metaTitle: The UUID aliases - Dotfiles (UK)
permalink: /aliases/uuid/

meta:
  - name: keywords
    content: aliases, uuid, linux, macos, shell, terminal, windows
  - name: twitter:card
    content: The UUID aliases create helpful shortcut aliases for the `uuidgen` command. The uuidgen command generates a Universally Unique IDentifier (UUID), a 128-bit value guaranteed to be unique over both space and time.
  - name: twitter:description
    content: The UUID aliases create helpful shortcut aliases for the `uuidgen` command. The uuidgen command generates a Universally Unique IDentifier (UUID), a 128-bit value guaranteed to be unique over both space and time.
  - name: twitter:title
    content: The UUID aliases - Dotfiles (UK)
  - name: og:title
    content: The UUID aliases - Dotfiles (UK)
  - name: og:description
    content: The UUID aliases create helpful shortcut aliases for the `uuidgen` command. The uuidgen command generates a Universally Unique IDentifier (UUID), a 128-bit value guaranteed to be unique over both space and time.
  - name: og:image:alt
    content: Dotfiles - Simply designed to fit your shell life
  - name: og:locale
    content: en_GB
---

# UUID aliases

The `uuid.aliases.zsh` file creates helpful shortcut aliases for generating
[UUIDs](https://en.wikipedia.org/wiki/Universally_unique_identifier).

The UUID aliases create helpful shortcut aliases for the `uuidgen` command.
The uuidgen command generates a Universally Unique IDentifier (UUID), a
128-bit value guaranteed to be unique over both space and time.

## UUID

[UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) is a 128-bit
number used to identify information in computer systems.

| Alias | Command                                                                            | Description                                   |
| ----- | ---------------------------------------------------------------------------------- | --------------------------------------------- |
| uuid  | `uuidgen \| tr -d '\n' \| tr '[:upper:]' '[:lower:]' \| pbcopy && pbpaste && echo` | Generate a UUID and copy it to the clipboard. |
