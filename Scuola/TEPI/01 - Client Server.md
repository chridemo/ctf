**MODELLO CLIENT-SERVER:** È costituito da applicazioni distribuite su diversi nodi. Chi richiede un servizio (client) utilizza il **livello applicativo** per generare un messaggio, chiamato **payload**, e lo passa al **livello di trasporto** che si occupa di impacchettarlo per la trasmissione.  

![[client_server 2.png]]

**PROTOCOLLI DI TRASPORTO:**

- **TCP (Transmission Control Protocol):** Protocollo **affidabile** ma meno veloce, garantisce la consegna dei dati e, in caso di errori, **richiede la ritrasmissione dei pacchetti**. Ideale per servizi come la **condivisione di file**.
    
- **UDP (User Datagram Protocol):** Protocollo **non affidabile** ma più veloce, **non richiede la ritrasmissione dei pacchetti** ed è adatto per servizi in tempo reale come lo **streaming**.
    

**PORTE E PROTOCOLLI:**

- **HTTP (Hyper Text Transfer Protocol):** Porta **80**, utilizzato per la **trasmissione di file HTML** e altri contenuti web. Utilizza **TCP**.
    
- **HTTPS (Hyper Text Transfer Protocol Secure):** Porta **443**, versione **sicura** di HTTP che utilizza una connessione **cifrata** per proteggere i dati.
    
- **DNS (Domain Name System):** Porta **53**, servizio fondamentale che **risolve un nome di dominio** (es. [google.com](https://google.com)) in un **indirizzo IP** numerico. Utilizza **UDP**.
    
- **SMTP (Simple Mail Transfer Protocol):** Porta **25**, protocollo per **l'invio** di messaggi di posta elettronica. Utilizza **TCP**.
    
- **SMTPS (Simple Mail Transfer Protocol Secure):** Porta **587**, versione **sicura** di SMTP che cifra la comunicazione.
    
- **POP3 (Post Office Protocol version 3):** Porta **110**, protocollo per **scaricare** i messaggi di posta dal server sul **client locale**, cancellandoli dal server, usa **TCP**.
    
- **IMAP (Internet Message Access Protocol):** Porta **143**, protocollo per la **gestione** della posta elettronica **direttamente sul server**, mantenendo i messaggi sincronizzati su tutti i dispositivi. Utilizza **TCP**.
    
- **FTP (File Transfer Protocol):** Porta **20** (trasferimento dati) e **21** (controllo), utilizzato per **l'accesso e il trasferimento di file** su un sistema remoto. Utilizza **TCP** e supporta modalità attiva e passiva.
    
- **TFTP (Trivial File Transfer Protocol):** Porta **69**, versione **semplice e non affidabile** di FTP, utilizzata per trasferire piccoli file senza autenticazione. Utilizza **UDP**.
    
- **TELNET (Terminal Network):** Porta **23**, protocollo per **l'accesso a un terminale remoto**, ma **non sicuro** in quanto i dati viaggiano in chiaro. Utilizza **TCP**.
    
- **SSH (Secure Shell):** Porta **22**, protocollo per **l'accesso a un terminale remoto in modo sicuro**, cifrando tutto il traffico. Utilizza **TCP**.
    
- **DHCP (Dynamic Host Configuration Protocol):** Porta **67** (server) e **68** (client), servizio che **assegna automaticamente un indirizzo IP** e altri parametri di rete a un host. Utilizza **UDP**.
    
- **IRC (Internet Relay Chat):** Porta **6667**, protocollo per **chat testuali** in tempo reale e notifiche istantanee. Utilizza **TCP**.

### **APPLICAZIONE DISTRIBUITA**

E' un applicazione composta da più elementi operanti tra di loro posti in esecuzione su macchine diverse. Livello applicativo I processi hanno l'obbiettivo di scambiarsi dei messaggi sia che siano nella stessa LAN o in due diverse.

### **PILA TCP/IP**

- **APPLICAZIONE**
- **TCP/UDP**
- **IP**
- **ETHERNET**

Ogni protocollo sceglie quale protocollo usare e a sua volta offre un servizio al protocollo superiore.

**API:** Mettono a disposizione gli strumenti di comunicazione.

**ASSOCIATION:** Struttura che identifica la porta al servizio. 

**SOCKET:** Permettono di instradare i messaggi nel loro percorso attraverso le porte logiche 2^16 da 0 65535. E' la coppia dell'IP associato alla porta.

FAMIGLIE DI SOCKET: Riunisce i socket che usano gli stessi protocolli:
**Stream Socket: 
Datagram Socket:
Raw Socket:**

**socket():** Metodo client e server
open()
close()
bind() 
listen()
accept()
connect()
sent() write()
recive() read()

**CALCOLO DISTRIBUITO:** Spezzo il codice e lo faccio eseguire da più macchine (cluster) che non condividono la stessa memoria ma comunicano tra di loro (send e recive). Due o più processi eseguite su più macchine scambiando messaggi e usando protocolli. 


 


















