# Casinò Grassi

Casino crawler in solitaria — gioco HTML5 a file singolo, giocabile direttamente nel browser.

## Come giocarci online (GitHub Pages)

Il repository include un workflow (`.github/workflows/pages.yml`) che pubblica automaticamente il sito su GitHub Pages a ogni push su `main`. Dopo il primo merge/push su `main`, il gioco sarà raggiungibile su:

`https://<utente>.github.io/casino-game/`

(controlla in **Settings → Pages** l'URL esatto e lo stato del deploy; in **Actions** trovi il log del workflow "Deploy to GitHub Pages").

## Come giocarci in locale

Apri semplicemente `index.html` in un browser moderno (Chrome, Firefox, Edge...), oppure servilo con un piccolo server statico:

```bash
python3 -m http.server 8000
```

e visita `http://localhost:8000`.
