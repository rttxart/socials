# socials — öffentlicher Card-Host für TX-Partner

Öffentlicher Bild-Host für Social-Media-Cards (TX-Partner). **Zweck:** Buffers API nimmt Bilder nur als öffentliche URL, nicht als lokale Datei — dieses Repo liefert die URLs, damit Cards als vollständige Buffer-Drafts (inkl. Bild) angelegt werden können (D-44-Recycle-Loop, 1-Klick statt 1-Drag).

- Nur veröffentlichte Marketing-Assets (Cards/PNGs) — **keine internen Daten**.
- Struktur: `cards/<YYYY-MM-DD-slug>/card-*.png`
- Raw-URL-Muster: `https://raw.githubusercontent.com/rttxart/socials/main/cards/<slug>/<datei>.png`
- Gerendert aus `brain/.claude/scripts/social/tweet-card/` (Vorlage `card-tx.html`).
