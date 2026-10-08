# Spiele der Mathe-Flüsterin

Übersichtsseite für `https://spiele.diemathefluesterin.net/`. Jedes Spiel liegt in einem eigenen Repo
und erscheint automatisch als Unterpfad dieser Domain (GitHub Pages, Projekt-Seiten unter der Custom Domain).

| Spiel | Repo | Adresse |
|---|---|---|
| Verliebte Zahlen | [SFPoldi/verliebte-zahlen](https://github.com/SFPoldi/verliebte-zahlen) | `/verliebte-zahlen/` |

## Neues Spiel hinzufügen
1. Neues Repo mit dem Spiel anlegen (Dateien im Hauptordner, `index.html` oben, relative Pfade).
2. Pages im Repo einschalten (Branch `main`, `/ (root)`).
3. Hier in `index.html` eine Kachel (`<li><a class="game" ...>`) ergänzen.

Eine eigene Domain ist derzeit **nicht** eingetragen (kein `CNAME`). Zum Veröffentlichen zuerst den DNS-Eintrag bei Wix setzen, dann die Domain in Settings, Pages eintragen (GitHub legt `CNAME` dabei selbst an). Einrichtung: siehe `docs/WIX.md` im Repo verliebte-zahlen.
