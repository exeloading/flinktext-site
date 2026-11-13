# flinktext-site

Öffentliche Webseite für Flinktext: Startseite, Hilfe, Vergleich, Datenschutz, Impressum (Deutsch, Englisch unter `en/`).

| Seite (DE) | Seite (EN) | Zweck |
|---|---|---|
| `vergleich.html` | `en/compare.html` | Überblick über Textbaustein-Programme, wann was passt |
| `flinktext-oder-phraseexpress.html` | `en/flinktext-vs-phraseexpress.html` | Einzelvergleich |
| `alternative-textexpander.html` | `en/textexpander-alternative.html` | Einzelvergleich mit Umstieg |
| `textbausteine-outlook.html` | `en/outlook.html` | Anleitung für Outlook |

Vergleiche nur sachlich und mit Quelle und Datum (§ 6 UWG). Angaben zu anderen Programmen haben den Stand 13.11.2026;
bei jeder größeren Änderung der Webseite kurz gegen die verlinkten Quellen prüfen und das Datum anpassen.
Reines HTML und CSS, keine Skripte, keine Cookies, keine fremden Schriften. Gedacht für GitHub Pages (Branch `main`, Ordner `/`).

## Vor dem Veröffentlichen

Alle Stellen mit `[AUSFÜLLEN: …]` bzw. `[FILL IN: …]` ersetzen (Name, Anschrift, E-Mail, ggf. USt-ID):

```
grep -rn "AUSFÜLLEN\|FILL IN" --include=*.html .
```

Danach unter Settings > Pages „Deploy from a branch“, `main`, `/ (root)` wählen. Adresse dann:
`https://exeloading.github.io/flinktext-site/` (Datenschutz: `…/datenschutz.html`, diese Adresse kommt ins Partner Center).

Der Knopf „Im Microsoft Store holen“ zeigt bis zum Release auf die Store-Suche nach „Flinktext“ (auf allen Seiten).
Nach dem Release kann er auf die direkte Store-Seite (`https://apps.microsoft.com/detail/<Store-ID>`) zeigen.

`sitemap.xml` und `robots.txt` nennen die Adresse `https://exeloading.github.io/flinktext-site/`. Kommt eine eigene Domain, beide anpassen.
Kampagnen-Links je Seite (z. B. `?cid=web-vergleich`) stehen im App-Repo unter `launch/KAMPAGNEN.md`.

Bilder in `img/` stammen aus `store/screenshots/` im App-Repo (`tools/storeshots/storeshots.js`), verkleinert auf 1600 × 900 (WebP).
