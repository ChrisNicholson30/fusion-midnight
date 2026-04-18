# Fusion Midnight — a Zed theme

A deep, OLED-friendly dark theme for [Zed](https://zed.dev/). Fusion Midnight takes the warm JetBrains syntax temperature of [New Darcula](https://github.com/e-simpson/new-darcula-z) and drops it onto the cool blue-gray UI chrome of [One Dark Pro Enhanced](https://github.com/hadez8877/one-dark-pro-enhanced) — like JetBrains syntax living inside Atom's UI shell, tuned darker.

<!-- Add a screenshot here once installed:
![Fusion Midnight preview](screenshots/preview.png)
-->

## Highlights

- **Deep editor background** — `#1c1f26`, easy on retina / OLED panels.
- **Saturated accents** — `#4dc4ff` blue for links & functions, `#f0a45d` amber for keywords & types.
- **Rainbow-bracket legibility** without a plugin — brackets in `#ffda5a`, delimiters in `#7a7a7a`.
- **High-contrast diffs** — red `#ff616e` and green `#a5e075` on tinted backdrops so `git diff` reads cleanly.
- **Italic comments** at `#7f838c` — present, not shouty.

## Install

### From the Zed extensions registry (once published)

1. In Zed: `cmd + shift + p` → **zed: extensions**.
2. Search **Fusion Midnight** and click **Install**.
3. `cmd + k cmd + t` → select **Fusion Midnight**.

### As a dev extension (right now, before registry publish)

1. Clone this repo: `git clone https://github.com/cn-design/fusion-midnight-zed`.
2. In Zed: `cmd + shift + p` → **zed: install dev extension** → point at the cloned folder.
3. `cmd + k cmd + t` → select **Fusion Midnight**.

### Drop-in (no extension machinery)

```bash
mkdir -p ~/.config/zed/themes
cp themes/fusion-midnight.json ~/.config/zed/themes/
```

Then `cmd + k cmd + t` in Zed.

## Palette

| Role | Hex | Where you see it |
| --- | --- | --- |
| Editor bg | `#1c1f26` | Main editor |
| Panel / sidebar | `#16181d` | Project tree, terminal panel |
| Tab bar | `#14171c` | Tab strip, title bar |
| Active line | `#232831` | Cursor row |
| Foreground | `#b7bfcf` | Default text |
| Keyword | `#f0a45d` | `if` / `for` / `return` / `class` |
| Function | `#4dc4ff` | Function names & calls |
| Type / class | `#ffd38a` | Type annotations |
| String | `#a5e075` | String literals |
| Number | `#f0a45d` | Numeric literals |
| Constant | `#b19dff` | `true` / `false` / `null` |
| Property | `#d1a3dd` | Object keys |
| Bracket | `#ffda5a` | `(){}[]` |
| Comment | `#7f838c` (italic) | `// ...` |
| Tag | `#ff616e` | JSX/HTML tags |

## Credits & inspiration

- [New Darcula for Zed](https://github.com/e-simpson/new-darcula-z) by Evan Simpson
- [One Dark Pro Enhanced](https://github.com/hadez8877/one-dark-pro-enhanced) by hadez8877

Neither project's code is included here — Fusion Midnight is an original palette inspired by both.

## Contributing

PRs welcome for:
- Additional variants (Dark / Warm / Light)
- Screenshots & language samples
- Fixes for syntax tokens that feel off in a language you use

## License

[MIT](LICENSE) — do anything, no warranty.
