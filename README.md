# slidev-theme-ember-modern-dark

A dark Slidev theme using Amazon's Ember Modern Display Standard font with a deep navy/charcoal aesthetic.

## Install

Add the following frontmatter to your `slides.md`. Start Slidev and it will prompt you to install the theme automatically.

```yaml
---
theme: ember-modern-dark
---
```

Or reference directly from GitHub:

```yaml
---
theme: https://github.com/efahsl/slidev-theme-ember-modern-dark
---
```

## Colors

| Token | Value |
|-------|-------|
| Background | `#1a1a1a` |
| Foreground | `#e8e8e8` |
| Primary | `#7eb3c7` |
| Accent | `#a8d5e2` |

## Fonts

- Sans: `Ember Modern Display Standard` (falls back to system sans-serif)
- Mono: `Fira Code`

## Customization

```yaml
---
theme: ember-modern-dark
themeConfig:
  primary: '#7eb3c7'
---
```

## Layouts

Includes all standard Slidev layouts: `cover`, `intro`, `section`, `fact`, `statement`, `quote`, plus the default layout.

## License

MIT License © 2024 [Eric Fahsl](https://github.com/efahsl)
