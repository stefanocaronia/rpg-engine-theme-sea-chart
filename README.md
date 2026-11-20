# Sea Chart

A theme for the dashboard of [rpg-engine](https://github.com/stefanocaronia/rpg-engine), for any game system: navy ink and brass on chart paper over a pale sea by day, sea foam on the night watch. Engraved small capitals for the titles, a book serif for the text, faint lines of latitude and longitude under the page and a compass star in the corner of the cards. Light and dark, both checked for contrast by the engine.

| | Light | Dark |
|---|---|---|
| Page | `#dde7e4` pale sea | `#071a24` night sea |
| Text | `#13283a` navy | `#e8efe9` |
| Accent | `#1b5f73` deep teal | `#7fd0e0` sea foam |
| Strong | `#e2ae4c` brass | `#e3b04f` brass |

## Its shapes

Cards with scooped corners, as a chart's cartouche, a graticule of faint lines under their words and a chart's neat line round them; buttons and tabs as pills, the tab chosen on a tint of teal; soft navy shadows; portraits in a thick ring of brass, like portholes; a coastal profile at the head of the page, hills, a light tower and the swell, beside the campaign's name; chart paper for the documents and the maps. The neat line comes from its own style sheet, `style.css`, which Settings can turn off while the rest stays. Needs rpg-engine 0.22 or later.

## Install

- In the dashboard: **Packages › Add**, paste `https://github.com/stefanocaronia/rpg-engine-theme-sea-chart`, or find it in the catalog under Themes.
- Or from a terminal: `rpg package install https://github.com/stefanocaronia/rpg-engine-theme-sea-chart`.

Then choose it in **Settings › This page › Game style**. It is installed for every campaign on this computer; `rpg package uninstall sea-chart` takes it away.

## Fonts

| Face | Used for | Licence |
|---|---|---|
| [IM Fell English SC](https://iginomarini.com/fell/), Igino Marini | titles | SIL Open Font License 1.1, `fonts/im-fell-english-sc/OFL.txt` |
| [Crimson Pro](https://github.com/Fonthausen/CrimsonPro), Jacques Le Bailly | text, story | SIL Open Font License 1.1, `fonts/crimson-pro/OFL.txt` |

Both come unchanged from [google/fonts](https://github.com/google/fonts).

## Licence

The theme, `theme.yaml`, `style.css` and `images/`, is © 2026 Stefano Caronia under [CC BY 4.0](LICENSE). The fonts stay under their own SIL Open Font License, beside each one.
