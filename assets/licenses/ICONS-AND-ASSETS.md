# Third-party assets bundled in the SVGs

All assets are embedded inside the SVG files (base64 or inline paths). No file is loaded from the network.

## Fonts (embedded as base64 WOFF2, Latin subset)
| Font | Use | Licence | File |
|---|---|---|---|
| Bricolage Grotesque Bold + Regular — © 2022 The Bricolage Grotesque Project Authors (https://github.com/ateliertriay/bricolage) | display + body | SIL Open Font License 1.1 | `BricolageGrotesque-OFL.txt` |
| JetBrains Mono Regular + Bold — © The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono) | mono labels | SIL Open Font License 1.1 | `JetBrainsMono-OFL.txt` |

The fonts were subset to Basic Latin plus a few punctuation/arrow glyphs and re-compressed to WOFF2 (permitted by the OFL; no Reserved Font Name is claimed here for the subset files, which are embedded only).

## Icons
* **Simple Icons** (https://simpleicons.org) — Python, C++, JavaScript, TypeScript, scikit-learn, pandas, NumPy, React, Next.js, Node.js, Express, PostgreSQL, MongoDB, Supabase, Git, GitHub. Licence: **CC0 1.0** (https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md). Path data was read from the `simple-icons` data shipped inside `react-icons` v5.6.0 (MIT packaging).
* **Java** is shown with the Simple Icons **OpenJDK** mark (Simple Icons has no Java mark). It is labelled "Java". Swap it for any mark you prefer.
* **LinkedIn** glyph: **Font Awesome Free 5** brand icon (`fa-linkedin`), © Fonticons, Inc. — licence **CC BY 4.0** (https://creativecommons.org/licenses/by/4.0/). Source: https://fontawesome.com/license/free . Simple Icons no longer ships a LinkedIn mark, and the official LinkedIn asset could not be downloaded in the offline build environment.
* **SQL, NLP, ML, API** have no brand mark; they are typographic monograms drawn with the display font.

All product names and logos are trademarks of their respective owners and are used only to label technologies.

## Images
`id.png` and `right_pointing.png` are the author's own images, embedded byte-for-byte.
