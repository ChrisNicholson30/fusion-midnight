# Fusion Themes for Zed



A warm-syntax-on-cool-chrome blend of [New Darcula](https://github.com/e-simpson/new-darcula-z) (JetBrains-feeling warmth) and [One Dark Pro Enhanced](https://github.com/hadez8877/one-dark-pro-enhanced) (Atom's cool blue-gray UI).

Three dark variants:

| Variant | Editor bg | Vibe |
| --- | --- | --- |
| **Fusion Dark** | `#23272e` | Balanced daily-driver. One Dark Pro chassis, New Darcula syntax warmth. |
| **Fusion Midnight** | `#1c1f26` | Deep/OLED-friendly, higher contrast, saturated accents. |
| **Fusion Warm** | `#2b2b2d` | Leans New Darcula. Warmer grays, JetBrains-style active line number. |

Shared syntax across all three keeps keywords in burnt-orange (`#d97934`), strings green, functions/types amber-blue, and brackets a JetBrains yellow (`#fcd247`) so you get rainbow-bracket legibility without a plugin.

## Install

### As a Zed dev extension (recommended)

1. Open Zed.
2. `cmd + shift + p` → **zed: install dev extension**.
3. Point it at this folder (`/Users/christophernicholson/Desktop/Theme`).
4. `cmd + k cmd + t` → pick **Fusion Dark**, **Fusion Midnight**, or **Fusion Warm**.

### Drop-in (no extension)

```bash
cp themes/fusion.json ~/.config/zed/themes/
```

Then `cmd + k cmd + t` in Zed.

## Tweaking

All three variants live in [themes/fusion.json](themes/fusion.json). Colors you might want to adjust:

- **Syntax hues** — each variant has its own `syntax` block at the bottom of its `style` object.
- **UI chrome** — `background`, `editor.background`, `panel.background`, `tab_bar.background`, `title_bar.background`, `status_bar.background`.
- **Accent** — search for `icon.accent` and `text.accent`.

## Credits

- **New Darcula for Zed** by Evan Simpson — <https://github.com/e-simpson/new-darcula-z>
- **One Dark Pro Enhanced** by hadez8877 — <https://github.com/hadez8877/one-dark-pro-enhanced>
