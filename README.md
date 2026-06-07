# Jens' Verjaardags-Avontuur 🎉

Een cartoon-platformgame voor Jens — gemaakt als verjaardagscadeau voor zijn 18e.

Eén enkel `index.html`-bestand, vanilla HTML/CSS/JS, geen frameworks, geen externe assets.
Werkt op de telefoon via de browser (touch-knoppen onderin) en ook met toetsenbord
(pijltjes + spatie) als bonus.

## Spelen

Open `index.html` lokaal in de browser, of host op GitHub Pages.

### GitHub Pages

1. Ga naar **Settings → Pages** van deze repo.
2. Source: **Deploy from a branch** — kies branch (bijv. `main`) en folder `/ (root)`.
3. Open de getoonde URL op de telefoon.

## Levels

1. **De Bakkerij** — verzamel broodjes en koffie ☕🥐
2. **Het Voetbalveld** — Ajax-veld, voetballen verzamelen ⚽
3. **Knolpower Feest** — eindfeest met confetti 🥔🎶

## Code aanpassen

In `index.html`:
- **Levels**: zie `LEVELS` array (platforms, items, vijanden, kleuren per level).
- **Speler-snelheid / sprongkracht**: constants `MOVE_SPEED`, `JUMP_V`, `GRAVITY`.
- **Kleuren / stijl**: CSS-variabelen in `:root` bovenaan.
- **Namen / teksten**: zie de overlay-`<div>`s in de HTML.

Veel plezier Jens! ❤️
Van Siebe, Mats &amp; Ole.
