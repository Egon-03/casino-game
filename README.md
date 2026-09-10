# Torre della Fortuna 3D

Casino crawler in solitaria — gioco HTML5 a file singolo, giocabile direttamente nel browser.

## Come giocarci online (GitHub Pages)

1. Vai su **Settings → Pages** in questo repository.
2. In "Build and deployment", scegli **Source: Deploy from a branch**.
3. Seleziona il branch `main` (o quello in cui è stato mergiato `index.html`) e cartella `/ (root)`.
4. Salva: dopo circa un minuto il gioco sarà online su `https://<utente>.github.io/casino-game/`.

## Come giocarci in locale

Apri semplicemente `index.html` in un browser moderno (Chrome, Firefox, Edge...), oppure servilo con un piccolo server statico:

```bash
python3 -m http.server 8000
```

e visita `http://localhost:8000`.
