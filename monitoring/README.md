<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Zug: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-25 08:19 UTC, Zug: Systematische Sammlung (bgs.zg.ch): 365 Adressen gelesen; 205 hinzugefügt, 0 geändert, 0 entfernt; Änderungen gefunden; 107 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Zug: Systematische Sammlung (bgs.zg.ch)](https://bgs.zg.ch/) | `<act>/` | täglich | 2026-11-25 08:19 UTC | Änderungen gefunden | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 08:10](checks/2026-11.md#ch-lexwork-zug-20261125t081018z) | lexwork-zug | 365 | 205 | 0 | 0 | 107 (0) | Änderungen gefunden | [174](https://github.com/lexifina/switzerland-zug-law/compare/b9766eac6c55...95831c158118) |
| [2026-11-24 12:51](checks/2026-11.md#ch-lexwork-zug-20261124t125117z) | lexwork-zug | 695 | 351 | 4 | 0 | 232 (0) | Änderungen gefunden | [285](https://github.com/lexifina/switzerland-zug-law/compare/22b4361caae5...2955492a38d0) |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
