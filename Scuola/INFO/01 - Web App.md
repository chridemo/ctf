**SITI WEB STATICI:** Presentano sempre le stesse info. e **non variano** nel tempo.

**SITI WEB DINAMICI:** Sono siti il cui **contenuto** delle pagine **varia** in base al tipo della scelta dell'utente. Hanno una struttura più complessa, possono essere usati anche da mobile e sono divisi in due parti: la parte di **back-end** che lavora sul lato server \dove corrono applicazioni come PHP e ASP e la parte di **back-end** che lavora sul lato client e utilizza JS e HTML.

**CMS (Content Management System):** Permette di caricare dei contenuti aggiuntivi come template per non partire da zero, es. WordPress, Giungla.

**WEB APPLICATION:** Sono applicazioni eseguibili attraverso un browser e sono un'evoluzione dei siti dinamici perché possono essere **utilizzati da qualunque dispositivo** che abbia accesso ad Internet a prescindere dell'OS. Possono essere utilizzate da più persone **contemporaneamente** e sono **scalabili** ossia **modificate** in base alle esigenze **con semplicità** facendo **un solo aggiornamento** per tutti i dispositivi e non una versione per ogni OS comportando un notevole **risparmio**. Sono utilizzate in più campi: e-commerce, finanza, istruzione, salute, produttività...

**INTRANET:** E' una **rete privata**, interna ad **un'azienda** che utilizza protocolli TCP/IP ed è **accessibile solamente ai membri autorizzati**.

**EXTRANET:** E' una rete simile all'intranet ma **permette l'accesso** anche ad **utenti esterni**.

**ARCHITETTURA WEB APP:** Si sviluppa principalmente su 3 livelli: presentazione, logico e dati.
![[webapp_architecture.png]]
- **LIVELLO DI PRESENTAZIONE:** Rappresenta l'interfaccia utente della web app e si occupa di acquisire e visualizzare dati. Può essere caratterizzato da linguaggi come HTML, JS.

- **LIVELLO LOGICO:** Si occupa di elaborare i dati in base ad un insieme di regole per fornire i risultati richiesti dall'utente. Qui avvengono le fasi relative alla gestione delle transazioni e alla sicurezza con le quali vengono effettuate grazie a protocolli come SSL/TSL.

  **CGI (Common Gateway Interface):** Permette di eseguire script su richiesta del client.

  **ASP (Active Server Page):** Applicazione lato server che permette di creare pagine web dinamiche generando contenuti HTML.

  **JAVA SERVLET:** Consente di eseguire classi Java su richiesta del client.

- **LIVELLO DATI:** Serve per gestire le informazioni contenute nel database che non sono direttamente accessibile attraverso web server, ad esempio server dati e mail server.

    ![[webapp_architecture_2.png]]