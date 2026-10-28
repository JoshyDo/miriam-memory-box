# Memory Box für Miriam ✨

Ein mobil-optimiertes, interaktives Geburtstags-Geschenkspiel für Miriam, gehostet über GitHub Pages.

## Aufbau & Features (7 Auspack-Stufen)
1. **Begrüßung & Audio-Freigabe:** Startscreen zur Freigabe des AudioContext auf Mobilgeräten.
2. **Schleife lösen:** Haptisches Wischen zum Schneiden und Lösen des Geschenkbands.
3. **Geschenkpapier auffalten:** 3D-Aufklappen der Papierflügel mit Knister-Sound.
4. **Zahlenschloss:** Vintage-Drehradschloss aus Messing mit konfigurierbarem Code (`2910`).
5. **Schatulle & Seidenpapier:** Deckel der Schatulle anheben und das zarte Seidenpapier mit Herzsiegel zur Seite lüften.
6. **Polaroids:** 4 interaktive Fotokarten mit 3D-Flip-Effekt und persönlicher Notiz auf der Rückseite.
7. **Brief & Finale:** Wachssiegel brechen, Konfetti-Animation, persönlicher Text und Spieldosen-Melodie.

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
