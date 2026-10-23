# Spedizioni Prime Stampa

Lettore PDF per Windows con gestione delle etichette di spedizione: fogli A4 a quattro posizioni, A6 e stampanti termiche.

Questo repository ospita la distribuzione dell'app e i cataloghi ufficiali dei preset.

## Download

È disponibile la [versione 0.5.0 per Windows x64](https://github.com/CommercialeSpedizioniPrime/spedizioni-prime-stampa/releases/tag/v0.5.0).

[Scarica l'installer 0.5.0](https://github.com/CommercialeSpedizioniPrime/spedizioni-prime-stampa/releases/download/v0.5.0/Spedizioni-Prime-Stampa-Setup-0.5.0.exe).

Le precedenti build locali richiedono questa prima installazione per attivare il canale degli aggiornamenti. L'installer registra l'app fra le applicazioni disponibili per i PDF; l'associazione predefinita resta una scelta dell'utente.

## Aggiornamenti

La versione 0.5.0 controlla le nuove versioni all'avvio e ogni 15 minuti mentre l'app è aperta. Serve una connessione Internet per rilevarle e scaricarle. Il canale è pubblico e non richiede account GitHub o abbonamenti ai clienti.

Gli aggiornamenti dell'app sono obbligatori: dopo il rilevamento di una nuova versione autentica, le nuove stampe vengono sospese. L'installazione attende la conclusione delle operazioni in corso e il salvataggio del lavoro. Le preferenze del cliente rimangono sul suo computer, comprese modalità PDF/Etichette, stampanti, formati, logo e personalizzazioni.

L'app verifica una firma Ed25519 e l'integrità dell'installer prima di eseguirlo. Questa verifica non equivale alla firma commerciale Windows: Windows può mostrare avvisi o impedire l'esecuzione di un installer non riconosciuto. Il programma non modifica le protezioni del sistema.

La pubblicazione separata dei cataloghi preset non è ancora attivata.

## Collaudo

Verificati download pubblico, firma e integrità dei file, obbligatorietà, salvataggio e ripristino su profili di prova. Il passaggio completo dell'installer da una versione alla successiva deve ancora essere provato su una postazione Windows dedicata. Le prove fisiche su stampanti e barcode restano necessarie per i singoli modelli e supporti.
