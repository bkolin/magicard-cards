# MagiCard card images

Static card-face images served over GitHub Pages for the MagiCard Android app's
"Remote Device Reveal" (NFC) feature. The app writes a URL like

    https://bkolin.github.io/magicard-cards/images/h13_1.png

to an NFC tag; scanning the tag on any phone opens the card image in the browser.

File names are `{suit}{rank}_{style}.png` where suit is `c`, `d`, `h`, or `s`,
rank is 1 (Ace) through 13 (King), and style is the face style (1 or 2).
