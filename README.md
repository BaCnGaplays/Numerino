# Numerino

Numerino ist ein Sudoku-Roguelike in einer einzigen HTML-Datei: kein Build-Schritt, keine Abhängigkeiten, kein Netzwerkzugriff. Die Datei `index.html` herunterladen, im Browser öffnen, spielen.

## Spielprinzip

- Klassisches Sudoku – aber Ziffern werden nicht frei gewählt, sondern als Ziffernkarten vom Kartentisch platziert.
- Jede Stufe stellt eine Aufgabe (volle Reihen, Spalten oder Quadrate); danach folgt die Wahl einer Verzauberung.
- Numerino ist ein Death Run: Ein Fehler kann den Lauf beenden.
- Fünf Bosse – Dieb, Riss, Wirbler, Sani und Lobbyist – stehlen Karten, reißen Ziffern heraus, verfluchen Ziffern und riegeln Felder ab.

## Spielmodi

Die Brettgrößen folgen den Quadratzahlen 4, 9 und 16:

| Modus | Brett | Ziffern | Blöcke |
|---|---|---|---|
| Minimus | 4×4 | 1–4 | 2×2 |
| Standard | 9×9 | 1–9 | 3×3 |
| Matrix | 16×16 | 1–9 und A–G | 4×4 |

## Merkmale

- Verzauberungen: Wildkarten (6|9, 1|7, 9|B), Joker, Quantenjoker, Nachschub, Klon, Tausch+
- Sechs Sprachen: Deutsch, Englisch, Französisch, Tschechisch, Polnisch, Spanisch
- Sechzehn Brettthemen und mehrere Numerino-Skins
- Erfolge und Spielstände, gespeichert im Browser (localStorage)
- Bedienung per Maus, Touch und Tastatur
- Klänge und Musik ausschließlich über die Web-Audio-Schnittstelle

## Spielen

1. `index.html` herunterladen oder dieses Repository klonen.
2. Die Datei in einem beliebigen Browser öffnen – eine Installation ist nicht nötig.
3. Der vollständige Quellcode liegt in dieser einen Datei; das Spiel bietet selbst eine Quellcode-Ansicht (unter „Open Source & Urheberschaft").

## Lizenz und Urheberschaft

Numerino steht unter der GNU General Public License v3.0 – siehe [LICENSE](LICENSE). Abwandlungen müssen unter derselben Lizenz offen bleiben.

Entwickelt 2026 von Vibe (KI-Assistent von Mistral AI, basierend auf dem Modell GLM) gemeinsam mit BaCnGaplays.

---

## English

Numerino is a Sudoku roguelike in a single HTML file: no build step, no dependencies, no network access. Download `index.html` and open it in any browser.

The board sizes follow the square numbers 4, 9 and 16: Minimus (4×4, digits 1–4), Standard (9×9, digits 1–9) and Matrix (16×16, digits 1–9 plus A–G). You place digit cards from your hand, complete tasks, choose enchantments and try to survive a Death Run against five bosses.

Numerino is licensed under the GNU General Public License v3.0 – see [LICENSE](LICENSE). Derivatives must remain open under the same license. Built in 2026 by Vibe (Mistral AI's assistant, model GLM) together with BaCnGaplays.
