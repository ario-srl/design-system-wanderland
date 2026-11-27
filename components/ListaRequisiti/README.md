Lista dei requisiti del veicolo nella sezione «Prima di partire» delle pagine itinerario: ogni voce ha un'icona dedicata, un nome e una riga di spiegazione.

**Cosa fornisce chi lo usa:** le voci (nome breve e spiegazione) e, per ognuna, l'icona del gruppo `assets/Icons/`.

- Box: sfondo `mist-25`, bordo 3px `mist`, raggio `radius-box` (25px), padding 35px (25px su mobile). Sta solo su sezioni chiare.
- Voci in colonna, separate da una linea 1px `list-divider`; la prima senza spazio sopra, le altre con 20px sopra e 26px sotto; l'ultima senza linea.
- **Icona:** 30 × 30px, a sinistra, allineata alla prima riga del nome; il testo rientra di 46px (30px di icona + 16px di distanza). Nessuna spunta ✔: l'icona la sostituisce.
- **Nome:** stile `requisito`, cioè DM Sans Bold 700, 17px, interlinea 1.25, `navy`, maiuscole e minuscole normali (niente maiuscolo forzato).
- **Spiegazione:** stile `body` (DM Sans 18px), colore `text-body`; 4.4px sotto il nome.
- Un'icona per voce e con un significato preciso: se una voce nuova non ha un'icona adatta, disegnala con le regole di `assets/Icons/README.md` prima di pubblicarla.
