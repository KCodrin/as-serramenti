# design.md — Design system

## Colori
| Token | Valore | Uso |
|---|---|---|
| --ink | #0e1012 | sfondi scuri, testo |
| --paper | #f4f2ee | sfondo chiaro |
| --brass | #b4925e | accento (ottone) |
| --brass-2 | #d4b483 | accento su scuro |
| --muted | #8b9096 | testi secondari |

## Tipografia
Inter Tight 300 per titoli grandi (lettere strette), Instrument Serif corsivo per le parole in evidenza (`<em>`).

## Componenti
Tutti in `index.html`: navbar con mega-menu, hero "finestra che si apre", marquee marchi, card prodotti, sezione feature con immagine fissa, passi del metodo, galleria orizzontale, CTA con modulo.

## Spazi e raggi
| Token | Valore | Uso |
|---|---|---|
| --sec | clamp(96px,11vw,168px) | spazio sopra/sotto ogni sezione |
| --gap | clamp(40px,6vw,96px) | spazio tra colonne |
| --h2 | Inter Tight 300, clamp(40px,5.2vw,84px) | tutti i titoli di sezione |
| --r / --r-lg | 20px / 28px | angoli di card e foto / blocco contatti |
| --brass-d | #97784a | parole in evidenza su sfondo chiaro |
