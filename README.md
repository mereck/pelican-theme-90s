# pelican-theme-90s

A neo-retro late-1990s theme for [Pelican](https://getpelican.com/). Windows 98 chrome, beveled borders, tiled backgrounds, navy toolbars, classic link colors, and a fake hit counter — all responsive for modern mobile browsers.

## Features

- Windows 98-style toolbar and beveled window frame
- Classic blue/purple/red link colors
- Pipe-separated navigation bar
- Sidebar with profile card, hit counter, and "best viewed in any browser" badge
- Borland-style syntax highlighting
- Mermaid diagram support
- Responsive layout — sidebar stacks below content on mobile
- System fonts only (Georgia, Tahoma, Courier New) — no web font downloads
- CC license support in footer

## Installation

Clone this repo and point your `pelicanconf.py` at it:

```python
THEME = "/path/to/pelican-theme-90s"
```

## Supported Settings

The theme reads these standard Pelican settings:

| Setting | Used for |
|---|---|
| `SITENAME` | Toolbar title and page titles |
| `SITEURL` | All internal links |
| `SITELOGO` | Sidebar profile image (e.g. `/images/profile.png`) |
| `AUTHOR` | Sidebar author name |
| `DEFAULT_LANG` | HTML lang attribute |
| `FEED_ALL_ATOM` | Atom feed link in nav and `<head>` |
| `DEFAULT_PAGINATION` | Pagination controls |
| `COPYRIGHT_YEAR` | Footer copyright |
| `COPYRIGHT_NAME` | Footer copyright |
| `CC_LICENSE` | Footer Creative Commons license link |

## License

MIT
