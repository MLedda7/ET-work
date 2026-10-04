# Tappeto gravitazionale: laboratorio con i telefoni

Tre file, da pubblicare insieme nella stessa cartella:

- `schermo.html` è la pagina da proiettare. Contiene il tappeto, il QR code e i comandi per chi conduce.
- `telefono.html` è la pagina che i ragazzi aprono dal QR code.
- `index.html` è la pagina d'ingresso, nel caso qualcuno apra l'indirizzo principale.

## Pubblicazione su GitHub Pages (una volta sola, circa 5 minuti)

1. Su github.com crea un nuovo repository, per esempio `tappeto-gravitazionale`, e impostalo come **Public**.
2. Nel repository scegli **Add file → Upload files**, trascina i tre file `.html` e conferma con **Commit changes**.
3. Vai in **Settings → Pages**. Alla voce *Build and deployment* scegli **Deploy from a branch**, poi il branch `main` e la cartella `/ (root)`, e premi **Save**.
4. Dopo uno o due minuti il sito è online all'indirizzo
   `https://TUO-NOME-UTENTE.github.io/tappeto-gravitazionale/`

Per aggiornare i file in futuro basta caricare di nuovo quelli nuovi con **Upload files**: sostituiscono i vecchi.

## Durante il laboratorio

1. Sul PC collegato al proiettore apri `https://TUO-NOME-UTENTE.github.io/tappeto-gravitazionale/schermo.html` e metti il browser a schermo intero (F11).
2. Quando nel pannello compare il pallino verde con la scritta "Pronto", i ragazzi possono inquadrare il QR code. In alternativa aprono l'indirizzo principale, scelgono "Partecipo con il telefono" e scrivono il codice di 5 lettere.
3. Il pulsante con i cursori, in alto a sinistra, nasconde il pannello dei comandi. Toccando il riquadro del QR code lo riduci a una piccola etichetta con il codice.

Comandi utili per chi conduce, nel pannello "Laboratorio con i telefoni":

- **Telefoni attivi**: toglilo per mettere in pausa tutti i telefoni mentre spieghi.
- **Pausa tra due azioni**: il tempo minimo tra due comandi dello stesso telefono. Con 25 ragazzi vanno bene 5–10 secondi.
- **Nuovo codice**: scollega tutti e genera una nuova stanza.
- **Prova un telefono in una scheda**: apre la pagina telefono in un'altra scheda dello stesso browser, per fare una prova senza telefono. Questa prova funziona anche senza internet.

## Cosa possono fare i telefoni

- **Aggiungi**: scegli il tipo di corpo e la massa. Tocca la mappa per posarlo, oppure trascina per lanciarlo.
- **Comanda**: tocca un corpo, poi scegli cosa fargli fare:
  - **Fai esplodere**: solo le stelle di almeno 8 masse solari. Una stella sotto le 20 masse solari lascia una stella di neutroni, una più pesante un buco nero. Se la massa è troppo bassa il telefono spiega perché, e si può aumentarla.
  - **Fai girare**: mette due corpi in orbita uno attorno all'altro.
  - **Fai scontrare**: lancia un corpo contro un altro.
  - **Cambia la massa**.

Quando una supernova perde molta massa, i pianeti che le orbitavano attorno possono scappare via: è fisica vera, non un errore, e vale la pena farlo notare.

## Se qualcosa non funziona

- **Sullo schermo compare "Server di collegamento non raggiungibile"**: il PC non è connesso a internet.
- **Sul telefono compare "Schermo non trovato"**: il codice non è giusto, oppure la pagina schermo è stata chiusa o ricaricata con un codice nuovo. Fai inquadrare di nuovo il QR.
- **Il telefono resta su "Collegamento…" a lungo**: alcune reti Wi-Fi scolastiche bloccano il collegamento diretto. Fai usare i dati mobili, oppure collega il PC all'hotspot di un telefono. Se succede spesso nella stessa scuola si può passare a Firebase, che funziona su quasi tutte le reti.
- **Lo schermo aperto con doppio clic dal computer** (indirizzo che inizia con `file://`) funziona solo per la prova in una scheda: i telefoni hanno bisogno dell'indirizzo di GitHub Pages.

## Privacy

Le pagine non salvano nulla. Il nome scritto dal ragazzo viaggia solo dal suo telefono allo schermo e compare nella proiezione: conviene dire di usare il nome di battesimo o un soprannome. Il server pubblico di PeerJS (0.peerjs.com) serve solo a far "trovare" telefono e schermo; poi i dati passano direttamente tra i due. Il codice stanza cambia a ogni sessione.

---
Strumento creato dal gruppo di divulgatori territoriali Einstein Telescope
