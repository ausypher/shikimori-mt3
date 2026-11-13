# Shikimori — Material Design 3 Expressive

A custom CSS theme for [Shikimori](https://shikimori.one/) inspired by **Material Design 3 Expressive**. It brings an expressive visual language to the Shikimori interface through a considered color palette, rounded shapes, tonal surfaces, typography, and carefully styled interface elements.

## Themes

- **Light — v0.3 (current)** — [Open stylesheet](Light/shikimori-m3-expressive_v0.3.css) · [Raw CSS](https://raw.githubusercontent.com/ausypher/shikimori-mt3/main/Light/shikimori-m3-expressive_v0.3.css)
- **Dark** — planned; not released yet.

Version **0.3** is the current Light theme. Previous releases are superseded; use v0.3 for all new installations and updates.

## Installation

You do not need to copy the entire CSS file. Shikimori can load the theme directly from GitHub using `@import`.

1. Open [Shikimori appearance settings](https://shikimori.one/profile/edit) and find the custom CSS field under **Settings → Site appearance → CSS**.
2. Paste this line into the CSS field:

```css
@import url("https://raw.githubusercontent.com/ausypher/shikimori-mt3/main/Light/shikimori-m3-expressive_v0.3.css");
```

3. Save your settings and reload Shikimori.

That's it — the theme will be loaded from this repository. You won't need to paste the full stylesheet manually.

### Updating the theme

Shikimori may cache imported stylesheets. If an update does not appear, reset the imported stylesheet cache using [Shikimori's style cache reset page](https://shikimori.one/tests/reset_styles_cache), then reload the page.

The Light stylesheet imports Roboto from Google Fonts; an internet connection may be required to load that font.

## Versioning

Light and Dark variants are maintained independently. The Light stylesheet's current release is **v0.3**. See [CHANGELOG.md](CHANGELOG.md) for the release history.

## License

Licensed under **GNU GPL-3.0-only**. See [LICENSE](LICENSE) for the full license text.

## Disclaimer

This is an independent community-made theme and is not affiliated with, endorsed by, or sponsored by Shikimori or Google. All trademarks belong to their respective owners.
