# doc.md — Stato attuale del progetto

> Ultimo aggiornamento: 2026-11-10

## Obiettivo
Nuovo sito di AS Serramenti (Torino). Per ora solo mockup della homepage da presentare al cliente.

## Stack
| Livello | Scelta | Note |
|---|---|---|
| Markup | HTML statico | un solo file `index.html`, CSS/JS inline |
| Font | Google Fonts | Inter Tight + Instrument Serif |

## Struttura delle cartelle
```
index.html     homepage mockup
assets/img/    foto (dal vecchio sito, ricompresse)
doc/           documentazione
kit-doc/       kit originale (modello)
```

## Come si lavora
- Avvio in locale: `python3 -m http.server 8791 -d Nuovo-Sito` (da file:// le foto si vedono nel browser normale, non nell'anteprima dell'app)
- Test: nessuno, controllo a schermo
- Pubblicazione: da decidere
