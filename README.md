# Lezione GPS — versione web installabile su iPhone

Questa è una Progressive Web App (PWA) per provare il flusso su iPhone senza Mac. Include:
- mappa OpenStreetMap;
- posizione GPS e percorso durante una lezione;
- tre pulsanti di errore con segnaposto e orario;
- storico locale delle lezioni;
- riepilogo finale per categoria;
- esportazione CSV.

## Importante: il pacchetto ZIP da solo non si installa
Per usare il GPS in Safari, il sito deve essere pubblicato su un indirizzo HTTPS. Non basta aprire `index.html` direttamente dal file ZIP o da File.

## Pubblicazione senza Mac
Puoi usare un servizio di hosting statico dal browser iPhone, ad esempio un provider che consenta di caricare una cartella o un archivio ZIP e pubblicarlo con HTTPS. Carica tutti i file contenuti in questa cartella mantenendo la stessa struttura. La procedura e le limitazioni dipendono dal servizio scelto; alcuni servizi richiedono un account.

## Installazione su iPhone
1. Apri l'indirizzo HTTPS pubblicato in Safari.
2. Premi il pulsante Condividi.
3. Scegli “Aggiungi alla schermata Home”.
4. Conferma “Aggiungi”.

## Uso
1. Apri Lezione GPS e consenti l'accesso alla posizione.
2. Premi “Nuova lezione”.
3. Quando è sicuro farlo, tocca il pulsante dell'errore.
4. Premi “Termina lezione” per il riepilogo.
5. Apri “Storico lezioni” per rivedere sessioni precedenti; scegli “Esporta CSV” per esportare gli eventi.

## Limiti e privacy
- I dati sono salvati nel browser sul dispositivo, senza account o cloud. Se cancelli i dati del sito/browser potresti perderli.
- La posizione viene tracciata mentre la pagina è aperta; il browser può sospendere il tracciamento in background.
- La mappa e Leaflet vengono caricati da Internet, così come le tessere cartografiche. Offline non è garantita la mappa.
- Il GPS può avere errori, specialmente in aree urbane.
- Prototipo da testare prima dell'uso reale. Non interagire con il telefono mentre il veicolo è in movimento se ciò può distrarre.
