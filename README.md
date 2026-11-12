# flinktext-site

Öffentliche Webseite für Flinktext: Startseite, Hilfe, Datenschutz, Impressum (Deutsch, Englisch unter `en/`).
Reines HTML und CSS, keine Skripte, keine Cookies, keine fremden Schriften. Gedacht für GitHub Pages (Branch `main`, Ordner `/`).

## Vor dem Veröffentlichen

Alle Stellen mit `[AUSFÜLLEN: …]` bzw. `[FILL IN: …]` ersetzen (Name, Anschrift, E-Mail, ggf. USt-ID):

```
grep -rn "AUSFÜLLEN\|FILL IN" --include=*.html .
```

Danach unter Settings > Pages „Deploy from a branch“, `main`, `/ (root)` wählen. Adresse dann:
`https://exeloading.github.io/flinktext-site/` (Datenschutz: `…/datenschutz.html`, diese Adresse kommt ins Partner Center).

Der Knopf „Im Microsoft Store holen“ zeigt bis zum Release auf die Store-Suche nach „Flinktext“.
Nach dem Release kann er auf die direkte Store-Seite (`https://apps.microsoft.com/detail/<Store-ID>`) zeigen.

Bilder in `img/` stammen aus `store/screenshots/` im App-Repo (`tools/storeshots/storeshots.js`), verkleinert auf 1600 × 900 (WebP).
