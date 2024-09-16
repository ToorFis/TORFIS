TORFIS - Calcolo Buste Paga
Descrizione

TORFIS è un'applicazione Python progettata per il calcolo delle buste paga. Questo strumento permette di gestire e calcolare diverse componenti del salario, come straordinari, indennità, trattenute e contributi. È particolarmente utile per professionisti delle risorse umane e contabili che necessitano di uno strumento flessibile e personalizzabile per il calcolo delle buste paga.
Motivazione

La gestione delle buste paga può essere complessa a causa delle numerose variabili e delle normative fiscali in continuo cambiamento. Con TORFIS, è possibile:

    Personalizzare i parametri: Modifica facilmente i valori dei parametri come la retribuzione tabellare, le indennità e le trattenute.
    Calcolare automaticamente gli straordinari: Inserisci le ore di straordinario e il sistema calcola automaticamente l'importo dovuto.
    Visualizzare dettagliatamente la busta paga: Stampa una busta paga dettagliata con tutte le componenti di competenze e trattenute.

Funzionalità

    Impostazione dei Parametri: Utilizza il metodo set_rettifica per aggiornare i valori dei parametri in modo dinamico.
    Calcolo degli Straordinari: Il metodo calcola_straordinari permette di inserire le ore straordinarie e calcolare il relativo compenso.
    Calcolo del Netto: Vari metodi come calcola_netto_verticale, calcola_netto_orizzontale, calcola_netto_semplice, calcola_netto_differenziale e calcola_netto_dettaglio forniscono diversi calcoli del netto in base a diverse modalità.
    Stampa della Busta Paga: Il metodo stampa_busta_paga stampa un riepilogo dettagliato della busta paga, evidenziando le competenze, le trattenute e il netto.

Come Utilizzare

    Imposta i valori iniziali: Crea un'istanza della classe BustaPaga e utilizza set_rettifica per personalizzare i valori.

    python

busta = BustaPaga()
busta.set_rettifica(retribuzione_tabellare=10.00, straordinario_forfait=1.50)

Calcola gli straordinari: Esegui il metodo calcola_straordinari e inserisci le ore di straordinario quando richiesto.

python

busta.calcola_straordinari()

Stampa la busta paga: Usa stampa_busta_paga per visualizzare i dettagli della busta paga.

python

    busta.stampa_busta_paga()

Esempio di Utilizzo

Il seguente codice mostra un esempio completo di utilizzo:

python

# Creazione dell'istanza
busta = BustaPaga()

# Esecuzione del calcolo straordinari
busta.calcola_straordinari()

# Stampa della busta paga
busta.stampa_busta_paga()

Contributi

Se desideri contribuire al progetto, sei il benvenuto! Apri una pull request con le tue modifiche e assicurati di spiegare le modifiche nel tuo messaggio di pull request.
Licenza

Questo progetto è concesso in licenza sotto la Licenza MIT. Consulta il file LICENSE per ulteriori dettagli.
