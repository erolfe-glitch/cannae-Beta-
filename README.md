# Cannae 216 v. Chr. (Beta)

Rundenbasiertes Hexfeld-Strategiespiel zur Schlacht von Cannae (2. August 216 v. Chr.).
Hannibal gegen Rom: Moral, Flanken, Einkesselung und Reiterei entscheiden die Schlacht.
Das Spiel schreibt nicht vor, was man tun soll, aber Hannibals historischer Plan funktioniert am besten.

## Spielen

- **Im Browser:** `index.html` öffnen (Doppelklick genügt). Keine Installation, kein Konto.
- **Online:** über GitHub Pages, sobald es für dieses Repo eingeschaltet ist.
- Läuft am PC, am Handy (quer halten) und gespiegelt auf dem Digitalboard.

## Spielmodi

- Als Hannibal gegen die KI (Rom)
- Als Varro & Paullus gegen die KI (Karthago)
- 2 Spieler gegeneinander an einem Gerät
- 2 Spieler gemeinsam als Karthago oder als Rom
- Historische oder eigene Aufstellung

## Aufbau

Alles steckt in einer einzigen Datei, `index.html` (HTML, CSS, JavaScript).
Die Spiellogik beginnt beim Abschnitt `// ===== CANNAE ENGINE`, die Oberfläche bei `// ===== UI =====`.

## Stand

Beta. Feld 26 × 16. Oberfläche wie bei Armargeddon: Schlachtfeld füllt den Bildschirm, schmale Statusleiste oben,
Einheitenkarte mit Bild unten, Ereignisse werden kurz eingeblendet, der ganze Bericht steht hinter dem Knopf „Bericht“.

- **Aufstellungsphase** vor jeder Schlacht: historische Aufstellung übernehmen oder frei verschieben.
- **Kräfteverhältnis** wählbar:
  - Historisch: KI gegen KI gewinnt Karthago 86 %, Rom 14 % (200 Schlachten).
  - Ausgeglichen: Roms Heer hält länger durch (bricht erst bei 80 % statt 65 % Ausfällen). KI gegen KI: Rom 48 %, Karthago 53 %.
