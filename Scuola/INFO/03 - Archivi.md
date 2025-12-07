**ARCHIVIO:** E' una **raccolta** organizzata **di informazioni** che possono essere gestite sia manualmente che automaticamente. E' quindi una **struttura dati costituita da un insieme di record**. Ogni record è identificato dalla posizione o indirizzo **fisico**.

**FILE:** E' un **insieme di registrazioni omogenee** memorizzate su memoria di massa. E' un archivio all'interno del quale si possono memorizzare informazioni sotto forma di byte.

"un archivio è sempre implementato da file ma non viceversa"

**RECORD:** Elementi che compongono il file, sono omogenei se contengono lo stesso tipo di informazioni nello stesso ordine. E' formato da un insieme di campi ognuno dei quali contiene info.

**TRACCIATO RECORD:** E' la struttura dei campi all'interno di un record e descrive per ognuno il tipo e la dimensione in byte.

**CHIAVE PRIMARIA:** Il campo univoco che identifica un record all'interno di un file (es. codice fiscale, id, codice).

**CHIAVE SECONDARIA:** Un campo che può essere assegnato a più record.

**RECORD LOGICO:** La descrizione di come il programmatore vuole suddividere le informazioni che vuole memorizzare.

**RECORD FISICO:** Rappresenta l'insieme di byte che possono essere letti o scritti in memoria di massa con una singola operazione di lettura o scrittura.

**ORGANIZZAZIONE FISICA:** Dipende dai supporti fisici.

**ORGANIZZAZIONE LOGICA:** Come i dati possono essere reperiti.

**LIMITI DEGLI ARCHIVI CLASSICI:** Se due applicazioni diverse lavorano sullo stesso file, e una deve scrivere alla struttura dati, bisognerà modificare anche la struttura dati presente nell'altra applicazione in modo da renderle omogenee. Allo stesso modo se un'applicazione deve leggere i dati deve conoscere la struttura. 

![[limiti_archivi.png]]


**UNICO CONTENITORE DATI:** Per risolvere il problema di più archivi, in modo che tutti i programmi e utenti possano accedere contemporaneamente e con semplicità ai dati.  

![[archivio_unico.png]]

**TEORIA DELLE BASI DI DATI:** Studia come organizzare al meglio grandi quantità di informazioni per poterle gestire in modo **semplice**, **efficiente** (spazio e velocità), **efficace** e **sicuro** (gestibili solo da utenti autorizzati).

**DATO:** Descrizione elementare di qualcosa, sono utilizzabili se siamo in possesso della loro **chiave di interpretazione**.

**SCHEMA:** Il significato che viene attribuito ad un dato per comprenderlo.

**ISTANZA:** Insieme dei valori assunti da uno schema in un certo istante.

**CATEGORIA:** Gruppo di dati con la stessa chiave di interpretazione.

**DBMS (Database Management System):** E' un insieme di programmi che gestiscono dei dati lasciando la loro gestione ai programmi applicativi (se prima ogni programma doveva interfacciarsi con il file system ora usa il DBMS). E' situato tra i programmi e gli archivi.

 **VANTAGGI:**
 
- **GESTIONE:** Creazione, inserimento, aggiornamento e interrogazione semplici.
- **INTEGRITÀ:** Informazioni omogenee grazie a dei vincoli.
- **NO RIDONDANZE:** Non ci sono ridondanze.
- **SICUREZZA:** Privatezza dei dati attraverso password e crittografia dei dati.
- **SUPPORTO TRANSAZIONI:** Operazioni con successo o insuccesso.
- **RIPRISTINO:** Backup e procedure di recovery dei dati.
- **ACCESSI CONCORRENTI**
- **GESTIONE DATI:** Contiene i "metadati", informazioni che descrivono il DB.
- **INDIPENDENZA DATI:** Consente l'utilizzo simultaneo di più utenti.

**DBA (Database Administrator):** Autorizza gli accessi, gestisce i dati, manutenzione DB, controlla la disponibilità di memoria e implementa il DB.

**PROGRAMMATORI:** Creano applicazioni per poter usare i dati del DB.

**UTENTI AVANZATI:** Accedono al DB e lo interrogano.

**UTENTI SEMPLICI:** Accedono al DB attraverso interfacce user friendly con grafiche.

**LIVELLI DI ASTRAZIONE DI UN DBMS**
Servono a nascondere all'utente la complessità e organizzazione dei nostri dati.
**LIVELLO ESTERNO:** Descrive i dati come sono visti da una o più applicazioni, ci accedono gli utenti attraverso specifiche applicazioni e permette di visualizzare o modificare i dati. 
**LIVELLO LOGICO:** Descrive tutti gli oggetti di interesse, fornendo una descrizione dettagliata dell'organizzazione dei dati.
**LIVELLO FISICO:** E' usato per la memorizzazione dei dati, qui si trova il DB fisico.

**VISTA:** E' l’astrazione di una parte del database creata apposta per l’utente.

Grazie all'astrazione dei 3 livelli otteniamo l'indipendenza logica e fisica dei dati.

**INDIPENDENZA FISICA:** Indica come e dove i dati sono archiviati su memoria di massa.
**INDIPENDENZA LOGICA:** Permette di modificare lo schema dei dati senza dover modificare i programmi che non sono interessati.