# Changelog

## 2026-11-10 · Homepage: spazi e coerenza visiva
**Cosa:** uniformati gli spazi tra le sezioni (un solo valore per tutte), i titoli delle sezioni (stessa misura), gli angoli arrotondati (due soli valori) e la dimensione dei testi introduttivi. La statistica "0€" diventa "Gratis". Le etichette sulle foto ora si leggono anche su foto chiare. La scritta grande del footer non viene più tagliata. Sistemato lo sfondo del blocco contatti, che restava troppo chiaro, e ridotti i margini su mobile.
**Perché / Dettagli:** richiesta del cliente: più coerenza visiva e percettiva. Nuovi token in `index.html`: `--sec`, `--gap`, `--h2`, `--r`, `--r-lg`, `--brass-d`.
**Verifica:** controllata a schermo su desktop (1440px) e mobile (375px), nessuno scorrimento orizzontale.

## 2026-11-10 · Mockup homepage v0.1
**Cosa:** creata la nuova homepage da zero (`index.html`, CSS e JS inline) e nuovo logo testuale "AS Serramenti" con simbolo a finestra. Navbar completa con menu a tendina ma voci non cliccabili (mockup). Modulo contatti solo visivo, non invia nulla.
**Perché / Dettagli:** presentazione al cliente in fase preventiva. Ispirazione: Oknoplast Pilar (sezioni scure, immagine fissa che cambia) e Framex. Testi e dati presi dal vecchio sito; nessun dato inventato. Foto copiate e ricompresse da `Sito-Vecchio/assets/img` in `assets/img/`.
**Verifica:** controllata a schermo su desktop (1440px) e mobile (~275px), nessun errore in console.
