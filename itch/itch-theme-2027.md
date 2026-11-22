# itch.io Jam Page Theme (2027 jam)

Settings for the AlgoJam itch.io jam page (**Edit theme** on the jam page), matching the dark theme of [algojam.org](https://www.algojam.org/). Reuse them for each new edition of the jam if using the same colors.

The colors come from the dark theme variables in `index.html`.

## Colors

| Setting | Value | Site variable |
|---|---|---|
| BG | `#0f2226` | `--bg` |
| BG 2 | `#163238` | `--card` |
| Text | `#e3f4f6` | `--fg` |
| Link | `#6fd8e8` | `--accent` |
| Headers | `#e3f4f6` | `--fg` |
| Button | `#6fd8e8` | `--accent` |

## Text

| Setting | Value |
|---|---|
| Font | Sans Serif (matches the site's system font stack, with no web fonts to load) |
| Size | Left at its default |
| Header font | Default font |

## Layout

| Setting | Value |
|---|---|
| Corners | Minimum (square, like the site's cards) |
| BG 2 opacity | Maximum |
| Shadow | None |

## Images

| Setting | Value |
|---|---|
| Banner | `banner-image.png`, from `banner-image.html` (transparent background) |
| Banner size | Fixed width |
| Background | `background-tile.png`, from `background-tile.html` |
| Background repeat | Both |
| Background size | Default |
| Background align | Left |
| Background fixed | Off |

Each source HTML file has the Edge command to re-render its PNG. The banner must be rendered with `--default-background-color=00000000` to stay transparent, so the page's repeating maze shows through it.

## Page content

- Jam description: `itch-page.html` (paste into the editor's HTML view). The markdown version is `itch-page-draft.md`.
- Submission page rules: `itch-submission-rules.html`. The markdown version is `itch-submission-rules.md`.
- The Discord link uses AlgoJam's own invite (`discord.gg/xM6A9ZMs58`), so joins from AlgoJam can be counted separately. Keep it.
