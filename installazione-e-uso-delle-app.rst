Installazione e uso delle app
=============================

Le App di valutazione sono distribuite sotto forma di file zip, contenenti l’eseguibile del programma e un file readme di istruzioni.

.. attention::

  L'app necessita di un computer con almeno 16GB di RAM per una corretta esecuzione.


Installare le app
---------------------

Vai sul `repository GitHub <https://github.com/italia/pa-website-validator-gui/releases/>`_, individua l’app corretta in base a sistema operativo e processore (macOS arm64, macOS Intel, Windows, Linux) e clicca per scaricare il file zip. 

Assicurati che la release sia l’ultima disponibile, contrassegnata dall’etichetta verde «Latest».

Abilitazione app su MacOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Potresti ricevere un avviso da MacOS che indica che l’app proviene da uno sviluppatore non riconosciuto. Per abilitare l’app, segui questi passaggi dopo aver scaricato il file ZIP:

1. apri il Terminale;
2. esegui il  comando `xattr -rd com.apple.quarantine DTD-AppDiValutazione-XYZ-mac.zip`.

Questo comando rimuove le restrizioni impostate dal sistema per consentire l’apertura del file.

Abilitazione app su Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Potresti ricevere un avviso da Windows che indica che l’app proviene da uno sviluppatore non riconosciuto. Per procedere con l’installazione, segui questi passaggi dopo aver scaricato il file ZIP:

- apri il file .exe;
- nella finestra di avviso, clicca su “Ulteriori informazioni”;
- clicca il pulsante “Esegui comunque” per avviare l’app.


Avviare una scansione
------------------------------

Nella tab "Nuova scansione":

1. Seleziona la **tipologia ente** (Comune o Scuola);

2. inserisci la **URL del sito** da scansionare, includendo il protocollo http:// o https://;

3. se vuoi modificare le **impostazioni avanzate**, clicca sulla barra per espandere la sezione e indica *accuratezza* (quante pagine scansionare), *quante pagine scansionare simultaneamente* e *timeout* (il tempo massimo di caricamento di ciascuna pagina, espresso in millisecondi);

4. seleziona i criteri e le raccomandazioni che vuoi verificare dalla lista. Puoi selezionarli o deselezionarli tutti cliccando su "Seleziona tutto";

5. clicca il pulsante "Avvia scansione" per avviare la scansione.

Avviata la scansione, non sarà più possibile modificare i dati e le preferenze, ma dovrai cliccare sul pulsante "Annulla scansione" e avviarne una nuova.

Durante la scansione, verranno visualizzati:

- le impostazioni avanzate selezionate (accuratezza, pagine scansionate simultaneamente, timeout);
- una barra di avanzamento della scansione;
- la lista dei log delle verifiche che l'app sta effettuando.



Visualizzare il risultato della scansione e accedere al report dettagliato
-----------------------------------------------------------------------------
Conclusa la scansione, si aprirà un resoconto riassuntivo che mostrerà:

- il risultato generale della scansione (OK verde per risultato positivo, KO rosso per risultato negativo, X rossa per errori nella scansione);
- una sezione espandibile "Criteri e raccomandazioni", con la lista delle verifiche svolte e il relativo risultato. In questa sezione puoi cambiare la selezione dei criteri e/o delle raccomandazioni e avviare una nuova scansione, cliccando sul pulsante "Riavvia scansione";
- una sezione espandibile "Consulta il log" con la lista dei log delle verifiche svolte dall'app.

Al clic sui pulsanti in altro a destra puoi visualizzare o scaricare il report dettagliato dei risultati. `Scopri come leggere il report dettagliato dei risultati </report-e-risultati.html>`_


Visualizzare lo storico delle scansioni
-----------------------------------------

Nella tab "Storico sansioni", puoi visualizzare tutte le scansioni effetuate.

Per ogni scansione, trovi le informazioni sulla tipologia di ente, l'url del sito, la durata, il risultato, i criteri superati, il totale dei criteri verificati, la data e l'ora.

Cliccando sui pulsanti di fianco ogni scansione, puoi:

1. vedere il dettaglio della scansione;
2. visualizzare il report dettagliato;
3. scaricare il report;
4. eliminare la scansione e il relativo report dallo storico.


