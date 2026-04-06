# Blu Alliance — Catalogo Interattivo 2026

Web app touch-friendly per tablet e browser.

## Come pubblicare su GitHub Pages

1. Crea un repository GitHub (es: `blu-alliance-catalog`)
2. Carica tutti i file di questa cartella nella root del repository
3. Vai su Settings → Pages → Branch: main → Save
4. Il catalogo sarà disponibile su: `https://tuousername.github.io/blu-alliance-catalog/`

## Uso su Tablet (modalità kiosk)

### Android (Chrome)
Apri Chrome e vai all'URL, poi:
Menu → "Aggiungi a schermata Home" → si installa come app fullscreen

### iPad (Safari)
Apri Safari e vai all'URL, poi:
Condividi → "Aggiungi a schermata Home"

## Struttura file
- `index.html` — app principale
- `slide-XX.jpg` — immagini delle schede barca

## Aggiornare i link di prenotazione
Nel file `index.html`, cerca `const URL_` per modificare i link delle singole categorie.
