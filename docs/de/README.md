<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <b>Deutsch</b> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a></p>

<p align="center">Der Werkzeugkasten für Netzwerk- und Systemadministratoren in einem Fenster: Erkennung, Pfad und Geschwindigkeit, DNS, Web, Mail, Fernverwaltung — ohne Installation, Treiber oder Konto.</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/ping.svg" width="760" alt="Ping-Sweep"></p>

<p align="center">✓ Eine Datei, keine Installation &nbsp;·&nbsp; ✓ Keine Administratorrechte nötig &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Daten bleiben auf dem Computer</p>

<p align="center"><a href="http://adminstools.org/downloads/AdminsTools-2.23.0.exe"><b>Windows</b></a> <sub>.exe · ~16 MB</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **27** | **1** | **256** | **5** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| Werkzeuge in einem Fenster | Datei; keine Installation | Adressen /24 in einer Runde | Sprachen: TR · EN · DE · RU · 中文 | Farbthemen, inklusive dunkel |

## Screenshots

| Erkennung | Pfad und Geschwindigkeit | DNS und Adresse | Web | Verwaltung | Konto und Info |
|---|---|---|---|---|---|
| [Ping-Sweep](#t-ping) | [Traceroute / MTR](#t-trace) | [DNS-Abfrage](#t-dns) | [HTTP/HTTPS-Übersicht](#t-http) | [Stapelverarbeitung](#t-exec) | [Subnetz berechnen](#t-subnet) |
| [Portscan](#t-port) | [Geschwindigkeitstest](#t-speed) | [Whois](#t-whois) | [HTTP-Anfrage (curl)](#t-curl) | [Mail](#t-mail) | [Dieser Computer](#t-local) |
| [IP-Identität](#t-ident) | [Wi-Fi](#t-wifi) | [Meine öffentliche IP](#t-myip) | [API-Client](#t-api) | [SNMP](#t-snmp) |  |
| [MAC-Hersteller](#t-mac) | [Datei-Downloader](#t-download) |  | [Zertifikat](#t-cert) | [Syslog](#t-syslog) |  |
| [Nachbarschaft (LLDP/CDP)](#t-nbr) | [MTU-Ermittlung](#t-mtu) |  | [SSL-Prüfung](#t-ssl) | [Port-Nachricht / Lauschen](#t-send) |  |
|  |  |  |  | [Paketaufzeichnung](#t-capture) |  |
|  |  |  |  | [Wake-on-LAN](#t-wol) |  |

### Erkennung

<a id="t-ping"></a>

#### Ping-Sweep

Ein /24 in einer Runde: Latenz, ARP, Verlust, Name und MAC-Hersteller; 5 Pings oder dauerhaft an eine Adresse.

![Ping-Sweep](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/ping.svg)

<a id="t-port"></a>

#### Portscan

Fertige Profile, Dienst-Banner, UDP-Sonden; riskante Ports markiert.

![Portscan](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/port.svg)

<a id="t-ident"></a>

#### IP-Identität

„Was ist diese IP?“ Ping, Ports, SNMP, Web und MAC ergeben eine begründete, bewertete Schätzung.

![IP-Identität](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/ident.svg)

<a id="t-mac"></a>

#### MAC-Hersteller

MAC → Hersteller in jedem Format; bei einer IP wird die MAC ermittelt. Virtuelle und lokal verwaltete Adressen markiert.

![MAC-Hersteller](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/mac.svg)

<a id="t-nbr"></a>

#### Nachbarschaft (LLDP/CDP)

Erkennung von Switch zu Switch; Portnamen, LAG, sieben Layouts, SVG / PNG / PDF.

![Nachbarschaft (LLDP/CDP)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/nbr.svg)

### Pfad und Geschwindigkeit

<a id="t-trace"></a>

#### Traceroute / MTR

Netzwerkspuren, Verlust und Latenz pro Hop, Weltkarte.

![Traceroute / MTR](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/trace.svg)

<a id="t-speed"></a>

#### Geschwindigkeitstest

Download-/Upload-Messung ins Internet oder zum eigenen Server.

![Geschwindigkeitstest](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/speed.svg)

<a id="t-wifi"></a>

#### Wi-Fi

Signalmesser, Kanalansicht und Abdeckungskarte.

![Wi-Fi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/wifi.svg)

<a id="t-download"></a>

#### Datei-Downloader

Schnelle Downloads über parallele Verbindungen, direkt in den Downloads-Ordner; SHA-256-Prüfung.

![Datei-Downloader](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/download.svg)

<a id="t-mtu"></a>

#### MTU-Ermittlung

Größtes Paket, das unfragmentiert durchkommt; Erkennung von Black Holes.

![MTU-Ermittlung](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/mtu.svg)

### DNS und Adresse

<a id="t-dns"></a>

#### DNS-Abfrage

Eintragstypen, mehrere Server nebeneinander vergleichen, DNSSEC, AXFR.

![DNS-Abfrage](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/dns.svg)

<a id="t-whois"></a>

#### Whois

RDAP und klassisches Whois: Registrar, Kontakte, AS, Standort, Rohdaten.

![Whois](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/whois.svg)

<a id="t-myip"></a>

#### Meine öffentliche IP

Ermittelt öffentliche Adresse, Provider und DNS-Umleitung.

![Meine öffentliche IP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/myip.svg)

### Web

<a id="t-http"></a>

#### HTTP/HTTPS-Übersicht

Statuscode, Weiterleitungen, Sicherheitsheader und Produkterkennung.

![HTTP/HTTPS-Übersicht](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/http.svg)

<a id="t-curl"></a>

#### HTTP-Anfrage (curl)

DNS, TCP, TLS und erstes Byte einzeln; auch Seiten, die JavaScript benötigen.

![HTTP-Anfrage (curl)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/curl.svg)

<a id="t-api"></a>

#### API-Client

Wie Postman, aber schlicht: Sammlungen, Variablen, Identität.

![API-Client](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/api.svg)

<a id="t-cert"></a>

#### Zertifikat

Kette, Ablaufdatum, Vertrauen und TLS-Versionen.

![Zertifikat](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/cert.svg)

<a id="t-ssl"></a>

#### SSL-Prüfung

Eine Note von A+ … F nahe an den SSL-Labs-Kriterien, mit Begründung.

![SSL-Prüfung](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/ssl.svg)

### Verwaltung

<a id="t-exec"></a>

#### Stapelverarbeitung

Befehle auf Hunderten von Rechnern per SSH / WinRM; Vorlagen, mehrere Identitäten.

![Stapelverarbeitung](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/exec.svg)

<a id="t-mail"></a>

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, Testnachricht und Relay-Test.

![Mail](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/mail.svg)

<a id="t-snmp"></a>

#### SNMP

Walk / Get, v1–v3; im Broadcast-Modus antwortet der Computer wie ein SNMP-Gerät.

![SNMP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/snmp.svg)

<a id="t-syslog"></a>

#### Syslog

Nachricht senden oder als Server eingehende Nachrichten empfangen.

![Syslog](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/syslog.svg)

<a id="t-send"></a>

#### Port-Nachricht / Lauschen

Nachricht an einen TCP- / UDP-Port senden und die Antwort oder eingehenden Verkehr beobachten.

![Port-Nachricht / Lauschen](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/send.svg)

<a id="t-capture"></a>

#### Paketaufzeichnung

Leichte Aufzeichnung ohne Npcap, Protokollübersicht und pcap-Speicherung.

![Paketaufzeichnung](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/capture.svg)

<a id="t-wol"></a>

#### Wake-on-LAN

Per Magic Packet aufwecken, und den Start per Ping verfolgen.

![Wake-on-LAN](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/wol.svg)

### Konto und Info

<a id="t-subnet"></a>

#### Subnetz berechnen

Netzwerk, Broadcast, nutzbarer Bereich, Maske und Aufteilung.

![Subnetz berechnen](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/subnet.svg)

<a id="t-local"></a>

#### Dieser Computer

Schnittstellen, adresler, Gateway, DNS und VPN.

![Dieser Computer](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/de/local.svg)

## Neden AdminsTools

- **Schnell, aber der Computer bleibt flüssig** — Pings gehen in gleichmäßigem Strom hinaus: Switches werden nicht überlastet, keine Antwort geht verloren. Das Programm läuft mit niedriger Priorität auf wenigen Kernen.
- **Starker Filter** — Fertige Schaltflächen, Wertelisten mit Anzahl, Bereiche und eine kurze Suchsprache: `vendor:hp rtt>20 -down`. Zeilen bleiben an ihrem Platz.
- **Ergebnisverlauf und Export** — Jeder Lauf wird aufbewahrt und unter seinem Namen gespeichert. Excel, CSV, pcap, SVG / PNG / PDF; Dateien direkt in den Downloads-Ordner.
- **Passworttresor** — SSH-, WinRM-, SNMP-v3- und Mail-Passwörter liegen in einem mit Argon2id + AES-GCM verschlüsselten Tresor; sie landen nie in Einstellungs- oder Ergebnisdateien.
- **Ihre Daten bleiben auf Ihrem Computer** — Kein Konto, keine Cloud, keine Telemetrie. Die Oberfläche öffnet sich nur auf 127.0.0.1 und mit Sitzungsschlüssel.
- **5 Sprachen, 9 Designs** — Türkisch, Englisch, Deutsch, Russisch, Chinesisch. Helle und dunkle Designs; Spaltenbreiten und Ansichten werden gespeichert.

## Herunterladen

Version 2.23.0 · Eine Datei: herunterladen und starten. Die Einstellungen stehen in einer Datei; legen Sie `PowerAdminTool.json` neben die exe, dann läuft es portabel vom USB-Stick.

**Windows** — `AdminsTools-2.23.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- Keine Installation und keine Administratorrechte nötig
- Ping und Traceroute ohne Treiber

[⤓ Für Windows herunterladen](http://adminstools.org/downloads/AdminsTools-2.23.0.exe)

**macOS** — `AdminsTools-2.23.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 und neuer) oder Intel
- Nicht signiert: beim ersten Start Rechtsklick › Öffnen
- Keine Paketaufzeichnung unter macOS

[⤓ Apple Silicon](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip)

**Linux** — `adminstools-2.23.0-linux-amd64 · ~15 MB`

- x86-64, eine einzige Binärdatei
- `-listen 0.0.0.0:8090` für den Browserzugriff auf einem Jump-Server
- Für Ping: `ping_group_range` oder `cap_net_raw`

[⤓ Für Linux herunterladen](http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64)

---

© 2026 Mehmet Göğebakan
