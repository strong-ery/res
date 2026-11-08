---
type: format
aliases: [<FormatName>]
extensions: [<.ext>]
game-version: <version this was verified on>
---

# {ext}

> This is the structure every format page follows. Delete this note and the bracketed hints when you copy it.

One sentence on what the format stores and where the game uses it. Eg: `.{ext}` files hold {what} and are loaded by [[{architecture-page}]].

## Layout

The structure from the first byte on, with the endianness stated once up top.

| Offset | Type | Name | Notes |
|---|---|---|---|
| `0x00` | `char[4]` | magic | `{magic}` |

## Compression and Wrapping

Whether the files ship compressed or inside an archive, and what it takes to open them.

## Tooling

- [[{tool-name}]] to read it, [[{tool-name}]] to write it

## Quirks

Things that behave differently from what the layout suggests, each with the symptom.
