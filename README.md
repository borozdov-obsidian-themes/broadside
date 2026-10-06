# Borozdov Broadside

A theme from the Borozdov collection. Two faces — light **Woodblock**, an old-world
broadsheet on grey newsprint, and dark **Soot**, the same sheet pulled from a sooty press.
Heavy colliding serif headlines, black banners, hairline rules and one ember stamp.

![Borozdov Broadside in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/broadside/main/screenshots/light.png)

![Borozdov Broadside in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/broadside/main/screenshots/dark.png)

## Principles

- **Display type is the brand.** Noto Serif Black for the title and the two largest
  headings, stacked so tight the lines nearly touch, like woodblock poster lettering; the
  text in the platform's serif.
- **Ink and newsprint.** Warm grey paper, never clinical, with bone-cream cards; ink black
  for type, rules and a black banner behind each top-level heading.
- **One ember stamp.** Tags are ember stamps in small capitals; ember also marks a checked
  task, the caret and callouts that signal trouble.
- **Print geometry.** 3px corners on what you press, 12px on cards with an ink shadow cast
  to the lower left; tables are ruled like a newspaper.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- A black banner behind each top-level heading in reading view
- Tags as ember stamps in small capitals
- Newspaper tables: heavy rules above and below, hairlines between rows
- Callouts as bone-cream cards with an ink shadow; trouble is titled in ember
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Broadside** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/broadside/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Broadside/`, then choose Borozdov Broadside under
Settings → Appearance → Themes.

## Font

Noto Serif Black (© 2015 Google LLC) is embedded in `theme.css` as base64 WOFF2 under the
SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). One weight, Latin and
Cyrillic, for the title and the two largest headings; the text uses your system's serif.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Гравюра» — старинный листок на
серой газетной бумаге, и тёмный «Сажа» — тот же лист из закопчённого пресса. Тяжёлые
теснящиеся заголовки (Noto Serif Black), чёрные плашки, волосяные линейки и одна огненная
печать. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Broadside в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
