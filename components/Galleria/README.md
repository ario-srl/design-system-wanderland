Galleria fotografica in prospettiva (effetto coverflow) che scorre in continuo, usata nelle pagine itinerario dopo la sezione «Viaggio».

**Cosa fornisce chi lo usa:** le foto (da 10 a 12) e un contenitore a tutta larghezza.

- Libreria Swiper 11.1.14, caricata solo quando la galleria sta per entrare in vista (400px prima).
- Effetto `coverflow`: rotazione 15°, profondità 100, modificatore 0.8, scala 1, nessuno stiramento, ombre delle slide attive.
- Slide centrate, larghezza automatica (`slidesPerView: 'auto'`), circa 300 × 300px, distanza 20px, a ciclo continuo (`loop`).
- Scorrimento automatico continuo: un passaggio ogni 9s (`speed` 9000) senza pause (`delay` 0), curva lineare. Si mette in pausa quando la galleria esce dalla vista e si ferma del tutto dopo che l'utente la trascina.
- Le slide hanno angoli di 12px e fondo `gallery-slide-bg` mentre la foto si carica; le foto coprono tutta la slide.
- Spazio verticale del contenitore: 115px sopra e 79px sotto (95px sopra su mobile).
- Si trascina con il mouse o con il dito: il cursore è una mano aperta, chiusa mentre trascini.
- Accessibilità: il contenitore è una regione con `aria-roledescription="carosello"` e `aria-label="Foto del viaggio"`.
- Con `prefers-reduced-motion` la galleria non scorre da sola.
