# ScoreHigh preview

Standalone preview with 25 simulated players. No real tournament results or
live Match Play API calls. Event display is designed for 1920×1080 monitors
and rotates through pages for larger fields.
Monitor page changes fade the whole standings board together without logo
interstitials. Reduced-motion preferences skip the animation.

This repository is separate from the production ScoreHigh site.
The dedicated monitor URL is monitor.html. The Monitor button on index.html
opens it directly; Exit display returns to index.html.
Page one shows the top
three card breakdowns and ranks 4–8 together. Later pages show the remaining
players, eight at a time, without the top-three cards. Games are visible for
each player. The whole board fades together between pages, without logo
interstitials. Image commas match the display font, with a small gap between
digit groups for readability. Machine blocks share colors by era and show
a small corner label (Old, Mid, or New). The top three cards have extra
vertical space. Each simulated player has a distinct six-game lineup,
with two games from each era in varied order.
The same updated display is also available at monitor-details.html.

Original scoring project: Elia Lake / arborelia, copyright 2026.
Original terms are retained in LICENSE.txt. Embedded font license notices
are included alongside the page (DSEG, Doto, Share Tech Mono, Sixtyfour, VT323).
7 Segment Display by Bernard Teo, based on Mylicia's “segment”, is used for
alphanumeric score digits. All ten digits have the same advance width.
The original archive, readme, and CC BY-SA 3.0 notice are included.
The seven-segment comma is the font's exact glyph outline, extracted as a
small SVG image to handle its zero-width text advance. This derived image
retains the same CC BY-SA 3.0 license and author attribution.
DS-Digital by Dusit Supasawat was used in the prior preview.
The original shareware notice and unmodified download archive are retained
as DS-Digital-LICENSE.txt and ds_digital.zip.
