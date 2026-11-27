Wanderland è un brand di viaggi in 4x4, in italiano, con tre linee: **Wanderland Labs**, **Wanderland Weekends** e **Wanderland Expeditions**. Il sistema si regge su crema e marrone scuro, un blu notte profondo, un oro tenue per le azioni e titoli in Feature Display.

## Contenuti e voce

- Scrivi in italiano. I bottoni sono verbi brevi all'imperativo: "Procedi", "Indietro", "Iscriviti". Le risposte del form sono "Sì" e "No".
- Scrivi "fuoristrada", non "off-road" (es. "90% fuoristrada").
- Scrivi il nome delle linee come "Wanderland" seguito dal nome della linea in grassetto: Wanderland **Labs**, Wanderland **Weekends**, Wanderland **Expeditions**.
- Il titolo di esempio della landing parte dalla prima persona plurale ("Progettiamo itinerari, viaggi, …") e mette in corsivo, con il gradiente oro, una sola parola chiave: "Insieme" nell'H1.

## Colore

- Ci sono due temi. `light` per le sezioni chiare, `dark` per quelle scure. Imposta `data-theme` sul contenitore della sezione.
- Sezioni chiare: `cream` (principale), `white`, `mist`. Sezioni scure: `umber` (marrone) e `navy` (blu notte). Nei temi usa `surface` e `surface-alt` invece dei valori fissi.
- Gli sfondi delle sezioni sono solo colori della palette, mai valori vicini a occhio (es. `#F8F7F5` o `#FAFAF9`). Nelle pagine itinerario: programma e offerta su `cream`, fascia dei dati su `mist-25` sopra il bianco, linea divisoria di 1px in `mist`. Il velo sulla foto di apertura è `overlay`.
- Titoli H1-H6 con `text-heading`: `navy` su sezioni chiare, `sand-96` su sezioni scure. Non usare `navy` come colore di testo su `navy`.
- Corpo del testo con `text-body`: `slate-70` su sezioni chiare, `sand` su sezioni scure (non `amber`). Le caption usano `text-caption`, con gli stessi colori.
- Sulle pagine del sito (fuori dai form) i bottoni sono **CTA di pagina**: etichetta `button-cta` (DM Sans Black 14px, maiuscolo, tracking 1.5px), alti 50px; vedi il componente Button.
- Il bottone principale è `button-bg` con testo `button-text`. Il bottone secondario "Indietro" vive solo su sezioni scure e usa `button-secondary-bg` e `button-secondary-border`. Tutti i bottoni hanno sempre `radius-pill`.
- I campi del form sono un bordino `field-border` di 1px su `field-bg` trasparente (19%; il select 12%, `field-select-bg`), con `radius-field`. Radio e checkbox usano `field-check` (#D2C8BB), mai blu.
- Oro (`gold`, `gold-glow`, `gold-light`, `gold-deep`) e salvia (`sage`) servono ad azioni, alla parola evidenziata e (solo `gold`) agli eyebrow, mai come sfondo di sezione.
- I colori del logo (`forest`, `ember`, `stone`) sono decorativi. `forest` si usa solo su sezioni chiare; `ember` e `stone` non vanno usati per testo piccolo.
- Tre coppie sono sotto la soglia 4.5:1 e restano esatte: `slate-70` come testo corrente sulle sezioni chiare (3.7-4.1:1), `button-text` bianco su `button-bg` (2.3:1) e gli eyebrow `gold` sulle sezioni chiare (2.0-2.3:1). Se ti serve la leggibilità piena, usa `slate` (solido) per il corpo e `navy` sul bottone (7.0:1), e dichiaralo.

## Tipografia

- I titoli H1-H4 usano Feature Display (stile `h1` … `h4`). `h1` è Regular 400; `h2` e `h3` sono Bold 700 (file `FeatureDisplay-NormalBold.ttf`), `h2-offerta` Medium 500; `h4` è Medium 500 (file `FeatureDisplay-NormalMedium.ttf`). La famiglia non ha un SemiBold: non dichiarare 600, che il browser renderebbe comunque con il Bold; per il Bold dichiara 700.
- Gli H2 di sezione misurano come gli H3: 36px, 30px su mobile (stile `h2`); la gerarchia la danno eyebrow e posizione. Il titolo della sezione offerta, quella con il prezzo, è un H2 con le misure di h1: stile `h2-offerta`, 55px (42px su mobile), Medium 500: a quella misura il Medium ha lo stesso peso visivo del Bold degli altri titoli (il Bold sembrerebbe più pesante). Regola generale: titoli più grandi usano un peso più leggero, perché lo spessore delle aste cresce con la misura.
- Nelle pagine itinerario, i numeri dei giorni («01», «02») usano `numero-giorno` (le misure di h1: 55px, 42px su mobile, Regular) e il prezzo usa `prezzo` (Feature Display Medium 70px su tutti i dispositivi). Il prezzo è volutamente più grande del titolo dell'offerta.
- H5 è DM Sans Semi Bold 600, 20px (`h5`). H6 è DM Sans Bold con tracking 3px (`h6`), senza trasformazione in maiuscolo.
- Gli eyebrow, le etichette brevi sopra i titoli H1-H4 ("IL PERCORSO", "PROGRAMMA"), vanno sempre in MAIUSCOLO: stile `eyebrow`, cioè DM Sans Bold 14px con tracking 3px e `text-transform: uppercase`, sempre in `gold` sia sulle sezioni chiare sia su quelle scure. Scrivi il testo normalmente e lascia il maiuscolo al CSS.
- Due etichette piccole, entrambe 12px, tracking 2px e sempre in maiuscolo via CSS: `etichetta-dato` (Regular, colore `text-heading`) sopra i valori della fascia dei dati, ed `etichetta-numerata` (Semi Bold, `gold`) per le sequenze «01 / …» sopra un titoletto. Non sostituiscono l'eyebrow, che resta l'etichetta sopra i titoli H1-H4.
- I dati sotto ogni giorno del programma («90 km», «Cena e notte incluse»), con la loro icona, usano `dato-giorno`: DM Sans Medium 14px, colore `text-heading`. Non sono caption.
- Il valore sotto `etichetta-dato` usa `valore-dato`: DM Sans Semi Bold 18px, la misura del `body` con il peso del Semi Bold, colore `text-heading`.
- Il corpo del testo è DM Sans Regular 18px (`body`); le caption sono DM Sans Light 14px (`caption`). I crediti delle foto in fondo alla pagina usano `crediti-foto` (DM Sans Light 12px, `sand`).
- Niente grassetto nel testo: nei paragrafi non usare `<strong>`, `<b>` o pesi Bold/Black per evidenziare parole o frasi. L'unica eccezione è il nome della linea (Wanderland **Weekends**), anche nelle caption delle polaroid. Una frase di chiusura che deve spiccare usa il colore `text-heading` con DM Sans Semi Bold 600 18px, come `valore-dato`.
- Su mobile usa `h1-mobile`, `h2-mobile`, `h2-offerta-mobile` e `h3-mobile`. Tablet, laptop e desktop condividono gli stessi valori; H4-H6, body e caption sono uguali ovunque.
- Per la parola evidenziata in corsivo usa Feature Display Regular Italic (file nel sistema).
- I font del sistema sono **solo due: DM Sans e Feature Display**. Non usare altri caratteri (per esempio Inter o Roboto), nemmeno per i titoli piccoli.
- DM Sans è un Google Font: caricalo dal CSS di Google Fonts nelle pagine che consumano il sistema (DM Sans 300, 400, 500, 600, 700, 900; il 900 serve all'etichetta delle CTA di pagina). Feature Display è un font con licenza: i file sono in `fonts/` e vanno caricati con `@font-face` come descritto in `tokens.json`.

## Forme, spazio e ombre

- I bottoni usano `radius-pill` (9999px, il massimo); i campi del form `radius-field` (4px).
- Le card polaroid usano `radius-card` (14px) per la cornice e `radius-photo` (10px) per la foto, con `shadow-polaroid`; la card in primo piano usa `shadow-polaroid-active`.
- Quando due card polaroid si sovrappongono, nessuna copre la caption dell'altra: in coppia sfalsata la prima (in alto a sinistra) sta sopra la seconda.
- La spaziatura documentata è quella dei componenti noti: `space-10` nei campi, `space-12` tra bottoni, `space-14` e `space-26` nelle cornici e nei bottoni, `space-18` sui bottoni stretti. Non esiste una scala generale: non inventare passaggi intermedi.
- Le foto hanno una leggera correzione: saturazione 0.95, contrasto 1.02.

## Movimento

- Effetto di lettura allo scroll: le parole passano da `read-off` a `read-on` (sezioni chiare) con una transizione colore di 200ms lineare.
- La parola evidenziata fluttua con un gradiente tra `gold-glow`, `gold-light`, `gold-deep` e `sage` in un ciclo di 5.2s.
- Le card a ventaglio si muovono con 420ms e curva `cubic-bezier(.2,.8,.2,1)`.
- La galleria fotografica scorre in continuo, lineare, con un passaggio ogni 9s (vedi componente **Galleria**).
- Transizioni di interfaccia, sempre con curva `ease`: colore dei link di navigazione 0.2s; sfondo (e colore) dei bottoni 0.2s; voci delle FAQ 0.3s per sfondo, bordo e ombra, 0.4s per lo spostamento.
- Focus da tastiera sempre visibile: contorno 2px `sand` con distanza 4px sui link e sui bottoni del menu, 2px `gold` con distanza 2px sulle domande delle FAQ; sui bottoni il focus ha lo stesso aspetto dell'hover.
- Rispetta sempre `prefers-reduced-motion`: niente animazioni, gradiente fermo, galleria ferma e scorrimento della pagina senza animazione.

## Logo e favicon

- Il simbolo esiste in tre versioni con sfondo trasparente: a colori (`forest`, `ember`, `stone`), sabbia (`sand`) e bianco. Usa quello a colori su `cream`, `white` e `mist`; sabbia o bianco su `umber` e `navy`.
- Non ridisegnare il simbolo: usa sempre i file del gruppo `Logos`.
- Per la favicon usa i PNG del gruppo `Favicon` (16, 32, 48, 64, 180, 192, 512 px). Per i loghi in pagina usa le versioni `-trim`, ritagliate sul simbolo.
- Il logo è disponibile solo come PNG, senza versione con la scritta né SVG.

## Immagini

Le immagini si definiscono per gruppi. Gruppi definiti finora: il ruolo del veicolo; colore e momenti di vita quotidiana.

### Il veicolo è un elemento secondario

Il fuoristrada non è mai il protagonista. Un'immagine Wanderland regge anche se togli il veicolo con la mente: restano il paesaggio e i suoi dettagli, l'emozione del viaggio, le persone, il gruppo e l'avventura nel suo complesso.

- Il veicolo occupa una frazione ridotta dell'inquadratura; il paesaggio (terra, cielo, acqua, bosco) ne occupa la maggior parte.
- Mai frontale e centrato come in un catalogo. Preferisci inquadrature laterali, lontane, di tre quarti, tagliate dal bordo o viste da dentro (cornice dello sguardo verso l'esterno).
- Per avvicinarti usa controluce e silhouette, sfocato di movimento, oppure dettagli: portapacchi, portiera aperta, fari accesi, un fuoco accanto.
- Le persone ci sono o sono evocate: di spalle, in silhouette, piccole nello spazio, in gruppo mentre fanno qualcosa. Non posano e non guardano in camera.
- Luce naturale (alba, tramonto, nebbia, pioggia, notte con luci calde); colori spenti e cinematografici, vicini a `forest`, `sand`, `ember`, `umber` e `navy`. Mai saturi.
- Il mezzo è scuro, datato e vissuto, con il portapacchi carico; non lucido né nuovo.
- Le targhe non devono essere leggibili: coprile o scegli un'altra foto.

**Da evitare:** veicolo in posa frontale come hero o in primo piano; foto da concessionario o da studio; veicoli dai colori vivaci che attirano più del paesaggio; scene senza persone né segni di vita con il mezzo solo al centro.

### Vita quotidiana, dettagli e colore

I viaggi Wanderland servono a scoprire il mondo. Le immagini cercano l'intensità in ciò che sembra banale.

- Momenti di vita quotidiana: sempre spontanei, mai in posa. Le persone sono impegnate in un gesto, di profilo, di spalle, tagliate o in silhouette; evita lo sguardo in camera. Il soggetto è il luogo, il gesto e l'atmosfera, non l'oggetto turistico.
- Paesaggio: fotografa un elemento di dettaglio apparentemente insignificante (una scaletta arrugginita, l'erba, un riflesso, la linea di un ruscello) con un taglio deciso, finché mostra tutta la sua bellezza. Lascia spazio al vuoto o alla texture.
- Luoghi noti: mostrali di lato, con una guida visiva (ruscello, strada, sentiero), non a figura intera da cartolina.
- Colore: viene dal luogo, mai aggiunto in post. Base calda e spenta, da pellicola leggermente sbiadita, con al massimo un accento vivo già presente nella scena (cassette, giubbotto, stufa, reti). Riferimenti ai token: ocra e rame vicini a `amber` e `gold`, il verde profondo a `forest`, il crepuscolo a `ember` e `umber`, gli azzurri freddi a `navy` e `stone`.
- Luce naturale e bassa (alba, tramonto, finestra, cielo velato); mai flash o luce da studio.

**Da evitare:** pose da catalogo e sorrisi in camera, scene pulite e sterili, colori saturati o neon in post, monumenti frontali da cartolina, composizioni piene e simmetriche senza respiro.

**Persone e luoghi riconoscibili:** se nella foto si vedono volti riconoscibili, nomi o numeri di imbarcazioni, targhe o simili, servono liberatorie o una scelta diversa prima dell'uso commerciale.

## Navigazione

- **Intestazione (desktop):** logo a sinistra e link a destra, distanziati di 36px. Stile `nav-link`: DM Sans Medium 16px, colore `nav-link` (`sand-96`), che diventa `white` al passaggio del mouse; nessuna sottolineatura. Da 1024px in giù i link si nascondono e compare il bottone del menu.
- **Menu mobile:** pannello a tutto schermo con sfondo `menu-bg` (`navy` al 98%) e logo in alto. Le voci usano lo stile `menu-link` (DM Sans Medium 26px, `nav-link`), allineate a sinistra, con 20px sopra e sotto e un separatore 1px `menu-divider` tra l'una e l'altra.
- Il menu si chiude con il bottone di chiusura, con il tasto Esc o toccando una voce. Mentre è aperto la pagina sotto non scorre e il focus passa al bottone di chiusura.
- Le icone del menu (apri e chiudi) sono tracciate in `sand`.

## Componenti

- **Button**: bottone principale e secondario del form multistep.
- **FormField**: campo di testo, select ed etichette radio su sezione scura.
- **PolaroidCard**: card polaroid con foto e caption "Wanderland **Linea**".
- **GradientWord**: parola evidenziata in corsivo con gradiente nell'H1.
- **Galleria**: carosello fotografico in prospettiva (coverflow) che scorre in continuo.
- **ListaRequisiti**: requisiti del veicolo con un'icona dedicata per voce, nome in DM Sans Bold e spiegazione.

## Icone

- Icone di linea, 24 × 24 mostrate a 30px, tratto 1.6 arrotondato, senza riempimento, colore `navy` sulle sezioni chiare. I file sono nel gruppo `assets/Icons/`.
- Un'icona per voce, con un significato concreto (per esempio lo schema del cambio per le marce ridotte). Non usare la spunta ✔ come icona.
