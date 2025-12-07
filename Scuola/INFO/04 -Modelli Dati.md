**MODELLO DATI:** E' l'**insieme delle strutture di dati** che consentono di **organizzare le informazioni del DB** per consentire le operazioni sui dati.

**MODELLO GERARCHICO:** **Precede** i **DB relazionali** ed è adatto a **rappresentare** casi in cui ci sono **entità che stanno in alto e altre in basso nella loro gerarchia**. Però sono complessi e quindi si passa ai DB relazionali.

**MODELLO RELAZIONALE:**  Il DB viene rappresentato come un **insieme di tabelle in relazione tra di loro**. E' considerato il modello più **semplice ed efficace** perché il più vicino al modo di pensare i dati. E' basato sulla relazione tra insiemi di oggetti (tabelle) sulle quali vengono effettuate operazioni. Ogni livello dei DBMS relazionali dispone di linguaggi specifici a seconda del livello:

**LIVELLO FISICO:** **DMCL** (Device Media Control Language) permette di definire i tipi di dati, i formati, le strutture di memorizzazione e i metodi di accesso.

**LIVELLO LOGICO:** **DCL** (Data Control Language) che permette di definire i permessi di accesso e **DDL** (Data Definition Language) che permette di definire le relazioni.

**LIVELLO ESTERNO:** **DML** (data Manipolation Language) che permette la manipolazione dei dati: inserimento, modifica, cancellazione di istanze e
**QL** (Query Language) che permette di interrogare i DB in base alle richieste.

**SQL (Structured Query Language):** E' il **linguaggio** di **interrogazione** usato nei **DBMS relazionali**.

**DB NoSQL:** Abbreviazione di **not only SQL** è un modello di progettazione di DB che consente la **memorizzazione e l'interrogazione** dei **dati** in modi **alternativi a** quelli presenti nei **DB relazionali**. Invece di utilizzare una struttura tabellare hanno una **struttura** non predefinita e **flessibile**.

In seguito alla **diffusione** di servizi web e **social media**, **videogiochi** e **IoT** che necessitano di **gestire** in tempo reale **grandi quantità di dati**. Si è notato quindi che i **DB relazionali richiedono** un notevole **dispendio** di risorse per gestire queste elevate moli di dati. I **DB NoSQL** offrono maggiore **scalabilità**, **flessibilità** e **velocità** nel **gestire** **grandi** dimensioni di **dati**.

# **CARATTERISTICHE:** 
- **Non usano** uno **schema predefinito** di dati: numero variabile dei campi.
- Esecuzioni di **query** (interrogazioni) **veloci** e complesse in tempo reale.
- Informazioni concentrate su **un solo archivio** evitando l'uso delle JOIN.
- **Scalabilità**: si adatta a **gestire** un **aumento** di **dati** e di richieste.
- **Frammentazione**: divisione dei dati in parti più piccole (shard) distribuiti su diversi server attraverso l'uso di **cluster** (gruppi di server).

# **TIPI DI DB NoSQL:**

**KEY-VALUE:** **Modello** dati **senza schema** organizzati in **dizionari** di **coppie chiave-valore**, ogni elemento ha una chiave e un valore. Vengono utilizzati per: dati sessione web app, raccolta dati degli utenti e gestione password

**COLUMNS FAMILY:** Evoluzione del key-value, **memorizzano informazioni** in **colonne**, consentono di **accedere solo** alle **colonne necessarie senza** allocare memoria per **dati irrilevanti**. Ad **ogni chiave** sono associati un **insieme di valori**. E' utilizzato per gestire dati finanziari e cronologie ricerche.

**DOCUMENTS:** Anch'essi si evolvono dal key-value, ogni **chiave** è **abbinata** ad un **oggetto** che **non possiede uno schema** predefinito. Solitamente vengono usati per catalogare prodotti e tracciare i log file. 

**GRAPHS** Sono DB che rappresentano le informazioni sotto forma di nodi e archi che li connettono. Ogni nodo rappresenta un elemento del quale si vogliono memorizzare i dati è un nodo con i corrispettivi attributi. Alcuni esempi sono: raccomandazioni acquisto e raccomandazioni musicali.