# EDI o *Blockchain* nella *Supply Chain*? #
Potrebbe la *Blockchain* rimpiazzare l'EDI?
La risposta dipende a sua volta dalle risposte ad altre domande
- Quali sarebbero i vantaggi?
- Avrebbe senso una integrazione dei due?
- Quale sarebbe, nel caso, la *blockchain* appropriata?
- Quali sarebbero, nel caso, i dati da conservare nella *blockchain*?

## EDI – la classica modalità di scambio di dati tra partner commerciali ##
L'EDI, per definizione, abilita lo scambio digitale di dati tra computer allo scopo di automatizzare i processi di business strutturando i dati e standardizzandone i formati.
Nello scambio EDI di documenti tra due partner, ad esempio per processare transazioni relative alla vendita di beni, le informazioni necessarie al partner vengono acquisite dai rispettivi sistemi informativi e convertite in un messaggio EDI standard, precedentemente concordato da entrambi gli attori. Successivamente essi possono interconnettersi e scambiare i propri messaggi EDI standardizzati per processare le transazioni attraverso sFTP, AS2, VAN, ...
L'elaborazione di una transazione EDI consiste quindi di due passaggi:
- [x] Definizione degli standard
- [x] Scambio. 
I *Trading partner* solitamente dialogano all'interno di una *supply chain* per la distribuzione dei loro prodotti via gomma, treno o nave. All'interno della *supply chain* tuttavia, intervengono spesso processi manuali e sostituzioni delle merci, che possono comportare problemi come ritardi, frodi (contraffazione delle merci o dei documenti) o persino il furto.
E quando infine, alla banchina arrivano i container di the, caffè o automobili, capita che alcuni operatori logistici inoltrino più volte il codice di raccolta a diverse società. Spesso è difficile tracciare l'effettivo destinatario dell'ordine di ritiro e come questo si sia aggiudicato il contratto. Anche quando si tratta di provare l'origine delle merci o il modo in cui sono state prodotte e le rotte che queste hanno seguito e attraverso quali intermediari non è facile avere trasparenza.
In altri termini, l'EDI è importante per conseguire uno scambio di dati e documenti automatizzato e regolare tra parti in relazione di *business* di lungo corso tra loro o che, già facendone uso, possono integrare nuovi flussi velocemente. Se ad una *Supply Chain* si dovessero aggiungere molti altri interlocutori, magari per singoli interventi nel corso di una transazione e che non utilizzano l'EDI, la situazione diventerebbe immediatamente complessa. Non solo perchè la catena della documentazione è discontinua ma anche perchè i dati potrebbero non essere standardizzati. Un'elaborazione all'interno del sistema EDI sarebbe sproporzionatamente onerosa per una singola transazione.
E' qui la *blockchain* potrebbe essere d'aiuto.

## Pro blockchain: ##
La *blockchain* è un argomento di tendenza da ormai alcuni anni. Semplificando la *blockchain* è un sistema di nodi che comunicano tra loro per consentire transazioni tra diverse parti. Qualsiasi modifica effettuata da uno degli attori in gioco viene intercettata e registrata da tutti i nodi. La combinazione di dati, tecnologia *distributed ledger* e *analytics* consente nuove funzionalità quali:
- Tracciabilità *end-to-end* in *real time*,
- Trasparenza,
- Consenso,
- *Smart Contracts*,
- *Peers* distribuiti con le stesse identiche copie dei dati,
- Crittografia,
- Immodificabilità,
- Irreversibilità.  
Questo rende questa tecnologia particolarmente sicura, sia in termini di manipolazione e resilienza agli attacchi, che di garanzia del recapito, contemplando inoltre la prova dell'originalità dei documenti.
Grazie all'approccio di condivisione della cronistoria digitale, è sempre possibile tracciare chi ha effettuato quali modifiche e quando. Ciò garantisce una documentazione completa, irreversibile ed inalterabile. Tali caratterstiche sono riconosciute come di particolare valore nella gestione della *Supply Chain* e delle Identità digitali. Per esempio, l'origine di una partita di the potrebbe essere tracciata risalendo fino al campo in cui è avvenuta la coltivazione. I componenti di un autoveicolo potrebbere essere ricondotti ai rispettivi produttori tramite i loro lotti di produzione (prova dell'utilizzo di ricambi originali) e si potrebbe risalire a tutti i precedenti proprietari senza timore di manomissione.
La gestione della situazione sopra descritta, con la connessione magari momentanea di nuovi trading partner sarebbe troppo complessa e lenta con l'EDI. Le *blockchain* possono essere estese rapidamente con *peer* aggiuntivi. Inoltre i *framework blockchain* facilitano la creazione di componenti di sistema che assumono rilevanza per la creazione di applicazioni distribuite e di *marketplace*, e vanno oltre la semplice conservazione dei dati nelle *blockchain*.  

### Nel caso, quale *Blockchain*? ###
Vi sono diversi tipi di *blockchain*. In generale, si potrebbe dire che queste stiano in relazione tra loro come Internet lo è con una Intranet.
* La *blockchain* pubblica è accessibile a chiunque (come Internet). Non vi è una istanza di controllo sovraordinata. Meccanismi quali *proof of work* o *proof of stake* vengono utilizzati per verificare ogni transazione effettuata. Gli esempi più noti di *blockchain* pubbliche sono Bitcoin, Ethereum e Algorand.
* La *blockchain* privata, preseguendo nell'analogia, corrisponde all'Intranet. E' accessibile solo ai partecipanti di un grupppo predefinito e vi sono dei responsabili incaricati del mantenimento che gestiscono e controllano azioni e diritti di accesso. Tali regolatori agiscono da garanti raggiungendo un consenso tra loro sulla concessione dei diritti di mining agli utenti. Ripple e Hyperledger Fabric sono *blockchain* private.
* Si può citare una terza variante: la *blockchain* federata(o consorzio). E' costituita solitamente da un gruppo di aziende o istituzioni finanaziarie responsabili di un network privato (la federazione o i consorzi). Le transazioni o le decsioni all'interno del network vengono verificate tramite codici definiti. Truffe o decisioni errate possono essere prevenute grazie a decisioni a maggioranza qualificata. Esempi di *blockchain* federate sono R3 per le aziende, EWF per le Utilities o B3i per il settore assicurativo.
* Forme ibride con meccanismi di autorizzazione pubblica o privata (*public-permissioned* o *private-permissioned*) vengono qui solamente citate.
I maggiori Cloud Service Provider (Alibaba, AWS, Azure, Google, IBM, Oracle, SAP, ...) si sono orientati verso Hyperledger Fabric 2 per implementare network B2B *permissioned*. Questo rientra nella categoria delle *blockchain* private. Gestisce diversi ledger. Le organizzazioni aziendali possono partecipare a diversi ledger e realizzare differenti *use case* e servizi per il proprio mercato. Gli sviluppatori delle *business application* traggono vantaggio della nuova gestione del codice della catena e dalle prestazioni migliorate.
Hyperledger Fabric permette raccolte private di dati e dati *off-chain*. Un'organizzazione può creare il primo *peer* già cosituendo così una *blockchain* pienamente funzionale. *Peers* aggiuntivi possono unirsi successivamente al network in espansione. Sopra questa *blockchain* si possono costruire *marketplace*, portali di manutenzione e supporto, network per la *delivery*, piattaforme o applicazioni *web*, andando così implicitamente a suportare un numero sempre maggiore di di *trading partner* e *use case*. I *peer* possono anche essere integrati con altre piattaforme *blockchain-enabled* quali Tradelens o WeTrade per lavorare con banche ed ecosistemi vari della *supply chain*.

### Nel caso,quali dati dovrebbero venire inseriti nella *blockchain*? ###
In linea teorica i documenti EDI potrebbero venire immagazzinati in un blocco e quindi rimpiazzare, ad esempio, una connessione AS2. Ma avrebbe senso? I documenti EDI contengono molte informazioni, alcune delle quali dovrebbero essere accessibili solo a determinati soggetti. Una possibile soluzione sarebbe la scrittura nella *blockchain* esclusivamente sulla base dei requisiti delle applicazioni previste. Ad esempio, nei casi in cui l'intero documento non sia richiesto per una certa applicazione, si potrebbe inserire nella catena solo l'hash di tale documento. In questo modo il contenuto del documento è composto rendendolo inalterabile e a prova di contraffazione. Per la maggior parte delle applicazioni sarà sufficiente un numero ridotto di dati inseriti, e.g. un codice articolo, un prezzo o un indicatore di qualità.
Inoltre distinguiamo tra dati c.d. *on-chain* e *off-chain*.

## Contro *blockchain*: ##
La *blockchain* è inefficiente rispetto ad un database relazionale.
In asssenza di un asset nativo che incentivi l'onestà di chi produce i blocchi, vi dovranno essere delle autorità centrali (i responsabili prima citati). Perchè questi dovrebbero utilizzare una struttura dati subottimale anzichè un database? La *blockchain* non è stata disegnata per essere come un database: le prestazioni in scrittura sono scarse e le capacità di interrogazione sono minimali.
- La necessità di una *governance* centralizzata,
- Il tema non risolto del tipo di consenso (distribuito, bilaterale, centralizzato),
- La definizione di quale sicurezza garantire (preventiva, investigativa o correttiva? Cosa succede se la fonte dei dati, gestita da una singola autorità viene hackerata?)
depotenziano l'utilizzo della blockchain in questo contesto.
Inoltre, è sicuramentge vero che, rispettando certi vincoli tecnologici, la *blockchain* può garantire una marcatura temporale, ma non può in ogni caso garantire la veridicità e l'accuratezza dell'informazione immessa nella catena. Qualunque oggetto sia stato registrato per essere poi pubblicato su un sito web potrebbe semplicemente essere falso.

## Conclusione: EDI o *Blockchain* per la *Supply Chain*? ##
Per i teorici della *blockchain*, dal punto di vista delle applicazioni e dei processi complessi che si verificano all'interno della *supply chain*, le proprietà di una *blockchain* hanno una senso.
Le *supply chain* includono partner che spesso utilizzano l'EDI. In tal caso solo i dati, estratti dai documenti EDI, rilevanti per l'applicazione e per la soluzione di un problema specifico vengono riportati nel ledger. Anche le altre informazioni richieste ma non fornite nello standard EDI utilizzato verranno riportate nella *blockchain*.
L'EDI potrebbe quindi venire semplicemente impiegato come punto di partenza ed agire come catalizzatore per queste applicazioni *blockchain*, dato che un partecipante EDI può attivare il primo *peer* nella *blockchain* e parte dei dati immessi nella catena vengono derivati automaticamente dall'EDI. In ogni caso, se i dati devono essere trasmessi da un partner ad un altro con un protocollo tradizionale, la tecnologia EDI sarà comunque utilizzata.

## Integrazione della *blockchain* ##
Non dovrebbe rappresentare un grosso problema connettere un *peer* di una *blockchain*, o delle piattaforme *blockchain*-enabled.
Il servizio di traduzione può mappare, convertire e generare i dati secondo le specifiche definite dai diversi ledger.
La gestione dei partner può essere integrata acquisendo le informazioni dalle diverse organizzazioni della *blockchain*.
I dati, provenienti da diversi connettori, quali KAFKA (Apache) o Digital Twins (Azure), possono essere spediti al *peer* della *blockchain*. Questo può automaticamente conservare il dato *off-chain* in un *Data Lake* (es:HDFS) e confrontarlo con gli hash presenti nella *blockchain*.
Si potrebbe inoltre integrare un Peppol Access Point con il *peer*.
