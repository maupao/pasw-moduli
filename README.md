# Moduli per il plugin Contact Form 7

## Avvertenza

Sto utilizzando github per le prime volte, è possibile quindi che ci siano dei commenti non esattamente centrati. I materiali a disposizione invece sono quelli che sto utilizzando nei siti scolastici da me seguiti.

## Indicazioni d'uso

I file per ora predisposti sono da utilizzare per il CMS WordPress con il plugin Contact Form 7. Per ogni modulo è presente il codice per la realizzazione del form e quello con le informazioni da inserire nel tab relativo all'ìnvio della mail in segreteria e per ricevuta al richiedente.

## Plugin necessari

Nella configurazione che sto usando ho installato questi plugin:

* Contact form 7
* contact form 7 datapicker
* Contact form DB, per visualizzare i dati raccolti. Non è presente nei repository dei plugin di wordpress, va installato caricando l'archivio zip dopo averlo [scaricato dal sito dell'autore](https://github.com/mdsimpson/contact-form-7-to-database-extension/releases)

## Un tocco di estetica

Gli elenchi di caselle di controllo sono gestiti di default in linea. In caso di elenchi lunghi è consigliabile fare in modo che le possibilità di scelta siano messe in colonna. Per fare questo è necessario aggiungere al foglio di stile questa riga:

<code>span.wpcf7-list-item { display: block; }</code>

Per esplorare altri piccoli miglioramenti di layout rimando alla [guida del sito](https://contactform7.com/custom-layout-for-checkboxes-and-radio-buttons/)

## Composizione della mail

La mail viene composta secondo il principio della ''Stampa unione''. Verranno quindi presi i dati immessi dall'utente e inseriti nella mail attraverso l'uso dei _[mail-tag]_. Nella parte superiore del riquadro sono elencati i mail-tag disponibili per la composizione della mail. Quelli non ancora inseriti nel testo sono evidenziati con il grassetto.

Nella scheda Mail è necessario mettere i segni di spunta su _"Escludi dall'output le linee con mail-tag vuoti"_ in modo che non vengano inseriti nella mail righe dove non ci siano informazioni e _"Utilizza contenuti in HTML"_ per avere la mail formattata con i tag html.

I tag possono essere inseriti anche nel campo A in modo da poter inviare la mail all'indirizzo di posta relativo a chi invia la domanda
