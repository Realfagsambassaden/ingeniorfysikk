# Ingeniørfysikk

Læreboka **Ingeniørfysikk** på [fysikkhjelp.no](https://fysikkhjelp.no/ingeniorfysikk/): fysikk for ingeniørstudenter (mekanikk, fluidmekanikk, svingninger og bølger, elektrisitet og magnetisme), med video, forelesningsnotater, eksempler og oppgaver med løsning. Kapitlene følger en vanlig universitetslærebok. Emnene IFYA1000 og IFYA1002 (NTNU) er løyper på fysikkhjelp.no som plukker ut det de trenger.

- `kapitler/` – én mappe per kapittel, én `.qmd`-fil per side. Hver side har `tema:` og `undertema:` øverst.
- `bilder/` – figurer og bilder.
- `figurer/` – TikZ-kilder til figurene. Kjør `python3 figurer/lag.py` for å tegne dem på nytt til `bilder/`.
- `fag.yml` – navn, status og nettsted.

Endringer på `main` publiseres automatisk (ca. 3–4 minutter). Se [BIDRA.md](BIDRA.md) for hvordan du skriver sider.

Innholdet bygger på donerte forelesningsnotater, fylt ut av Claude. Det som er lagt til, er merket med `<!-- tillegg: Claude -->` i kildeteksten.
