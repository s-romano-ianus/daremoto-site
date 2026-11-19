# daremoto.net

Sito vetrina di DareMoto (Ianus Project): home, download, supporto, privacy.
HTML e CSS statici, senza build, pubblicati con GitHub Pages sul dominio `daremoto.net` (file `CNAME`).

- Palette e loghi: cartella `brand/` del client (`s-romano-ianus/rustdesk`, ramo `custom`).
- Download: link fissi a `releases/latest/download/daremoto.exe` e `daremoto-install.exe`
  della fork del client. Per una nuova versione basta pubblicare la release; aggiornare
  il numero di versione in `download/index.html`.
- Niente risorse di terze parti (font, script, statistiche): l'informativa lo dichiara.

Anteprima locale: `python -m http.server 8000` nella cartella, poi http://localhost:8000
