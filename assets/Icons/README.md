Icone di linea di Wanderland, disegnate per le pagine del sito.

- Griglia 24 × 24 (`viewBox="0 0 24 24"`), mostrate a 30px.
- Solo tratto, senza riempimento: spessore 1.6, estremità e giunzioni arrotondate.
- Colore `navy` (#182433) sulle sezioni chiare.
- Una sola icona per voce, con un significato concreto: niente decorazioni generiche.

Icone dei requisiti del veicolo (componente **ListaRequisiti**):

| File | Voce |
|---|---|
| `icona-marce-ridotte.svg` | Marce ridotte (schema del cambio) |
| `icona-gomme-all-terrain.svg` | Gomme All-terrain o Mud-terrain (pneumatico con battistrada) |
| `icona-gomme-neve-catene.svg` | Gomme M+S o catene da neve (fiocco di neve) |
| `icona-ruota-di-scorta.svg` | Ruota di scorta (cerchio con razze) |
| `icona-radio-cb.svg` | Radio CB o PMR (ricetrasmittente) |
| `icona-ganci-recupero.svg` | Ganci e attrezzature di recupero (grillo) |

Su WordPress il caricamento di SVG è disattivato: sulle pagine le icone sono inserite come immagine in linea (`data:image/svg+xml`, codificata) nello pseudo-elemento `::before` della voce.
