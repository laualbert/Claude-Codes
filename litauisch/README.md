# Litauisch in 1 Stunde 🇱🇹

Kleine Offline-Lern-App (PWA) für die wichtigsten litauischen Sätze: grüßen, verabschieden,
danke, bitte, nach dem Preis fragen, bestellen und höflich auf Englisch wechseln.

- 6 Lektionen à ca. 10 Minuten: **Lernen → Üben → Mini-Dialog**
- Abschlussprüfung über alles
- Bonus-Lektion 7 „Flirten in der Bar 🍸“ (sofort freigeschaltet)
- Spickzettel mit allen Sätzen und Ausspracheregeln

## Vor dem Flug (wichtig!)

1. Die Seite **einmal mit Internet** öffnen.
2. Unten warten, bis **„✓ Offline verfügbar“** steht.
3. Zum Home-Bildschirm hinzufügen:
   - **iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“
   - **Android (Chrome):** Menü ⋮ → „App installieren“ bzw. „Zum Startbildschirm hinzufügen“
4. Flugmodus an, App vom Home-Bildschirm starten. Fertig.

Der Fortschritt wird lokal im Browser gespeichert. Unten in der App kannst du ihn zurücksetzen.

## Technik

Reines HTML/CSS/JS ohne Build-Schritt. `sw.js` cacht alle Dateien. Nach Änderungen die
`CACHE`-Version in `sw.js` erhöhen, damit das Update auch auf installierten Geräten ankommt.
