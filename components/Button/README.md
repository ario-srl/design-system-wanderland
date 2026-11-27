Il bottone di Wanderland in due varianti: il **bottone dei form** multistep (principale oro per avanzare o iscriversi, secondario trasparente per tornare indietro) e la **CTA di pagina**, i bottoni delle pagine del sito (in fondo a questo file).

**Cosa fornisce chi lo usa:** l'etichetta (verbo breve in italiano: "Procedi", "Iscriviti", "Indietro") e il contenitore.

- Il principale usa `button-bg` con testo `button-text`. È l'unico bottone pieno di una schermata.
- Il secondario ("Indietro") usa `button-secondary-bg`, bordo 2px `button-secondary-border` e testo `button-secondary-text`; vive solo su sezioni scure.
- Padding `space-14` in verticale e `space-26` in orizzontale (`space-18` sotto i 420px); gap `space-12`; font DM Sans 13px (12px sotto i 420px), line-height 1.1, testo su una riga.
- Su due bottoni affiancati dividono lo spazio in parti uguali; sotto i 340px si impilano.
- Raggio sempre `radius-pill` (9999px, il massimo): tutti i bottoni, principale e secondario, sono a pillola, anche a larghezza piena.
- Il testo bianco su oro ha contrasto 2.3:1: valore della sorgente, da migliorare solo se lo decidi tu. Stati del bottone principale:
- **Hover e focus da tastiera** (`:hover`, `:focus-visible`): sfondo `button-hover-bg` (`gold-deep`), testo invariato (3.9:1); transizione dello sfondo 0.2s `ease`.
- **Disabilitato** (posti esauriti): sfondo `button-disabled-bg` (#BDBAB5), testo `button-text`, nessun hover. È l'unico caso in cui l'etichetta non è un verbo all'imperativo: si scrive «Sold out». Contrasto 1.9:1, ammesso perché il bottone non è utilizzabile.
- Gli stati del bottone secondario non sono ancora definiti.

## CTA di pagina

I bottoni delle pagine del sito (apertura, «Prima di partire», offerta), fuori dai form. Hanno valori propri, più grandi e marcati del bottone dei form.

- Etichetta stile `button-cta`: DM Sans Black 900, 14px, interlinea 14px, tracking 1.5px, sempre in maiuscolo via CSS (scrivi il testo normalmente: «Scrivi a Roberto»). Verbi brevi all'imperativo; l'unica eccezione è «Sold out».
- Alta 50px su tutti i dispositivi: padding verticale 18px, orizzontale `space-42` (42px) nell'apertura e `space-51` (51px) nelle altre sezioni. Nell'apertura la CTA principale è larga almeno 249px. Raggio `radius-pill`.
- **Principale:** sfondo `button-bg` (`gold`), testo `button-text` bianco (2.3:1, valore mantenuto); hover e focus `button-hover-bg` (`gold-deep`), transizione dello sfondo 0.2s.
- **A contorno** (solo su sezioni scure o sulla foto dell'apertura, accanto alla principale): sfondo trasparente, bordo 1px `button-outline-border` (`gold`), testo `button-outline-text` (`gold`); padding 17px × 41px per compensare il bordo, così è alta 50px come la principale. Hover e focus: si riempie di `button-outline-hover-bg` (`gold`) con testo `button-outline-hover-text` (`navy`); transizione di sfondo e colore 0.2s.
- **Disabilitata** (posti esauriti): sfondo `button-disabled-bg`, testo bianco, etichetta «Sold out», nessun hover.
- Una sola CTA piena per schermata; nell'apertura si affiancano la principale e quella a contorno, con 17px di distanza. Su mobile vanno in colonna, a 19px di distanza, e hanno **la stessa larghezza**: entrambe a tutta la larghezza del contenuto, allineate ai margini del testo.
