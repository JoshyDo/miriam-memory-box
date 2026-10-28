# Memory Box für Miriam ✨

Ein mobil-optimiertes, interaktives Geburtstags-Geschenkspiel für Miriam, gehostet über GitHub Pages.

## Aufbau & Features
1. **Begrüßung & Audio-Freigabe:** Startscreen zur Freigabe des AudioContext auf Mobilgeräten (iOS Safari / Android Chrome).
2. **Schleife lösen:** Haptisches Wischen zum Öffnen des Geschenkbands.
3. **Zahlenschloss:** 4-stelliges Drehrad-Schloss mit konfigurierbarem Code und Hinweisfeld.
4. **Polaroids:** 4 interaktive Fotokarten mit 3D-Flip-Effekt und persönlicher Notiz auf der Rückseite.
5. **Brief & Geschenk:** Siegel brechen, Konfetti-Animation, persönlicher Text und Spieldosen-Melodie.

## Anpassung
Alle Inhalte können direkt in der `index.html` im `CONFIG`-Objekt angepasst werden:

```javascript
const CONFIG = {
  recipientName: "Miriam",
  passcode: "2910",
  passcodeHint: "Tipp: Dein Geburtstag im Format (TT.MM) ✨",
  polaroids: [ ... ],
  letter: { ... }
};
```
