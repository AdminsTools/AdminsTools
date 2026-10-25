<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="../../assets/wordmark-dark.png"><img src="../../assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <b>Deutsch</b> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a></p>

<p align="center">Der Werkzeugkasten für Netzwerk- und Systemadministratoren in einem Fenster: Erkennung, Pfad und Geschwindigkeit, DNS, Web, Mail, Fernverwaltung — ohne Installation, Treiber oder Konto.</p>

<p align="center">✓ Eine Datei, keine Installation &nbsp;·&nbsp; ✓ Keine Administratorrechte nötig &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Daten bleiben auf dem Computer</p>

## Screenshots

### Erkennung

#### Ping-Sweep

Ein /24 in einer Runde: Latenz, ARP, Verlust, Name und MAC-Hersteller; 5 Pings oder dauerhaft an eine Adresse.

![Ping-Sweep](../../assets/screens/de/ping.svg)

#### Portscan

Fertige Profile, Dienst-Banner, UDP-Sonden; riskante Ports markiert.

![Portscan](../../assets/screens/de/port.svg)

#### IP-Identität

„Was ist diese IP?“ Ping, Ports, SNMP, Web und MAC ergeben eine begründete, bewertete Schätzung.

![IP-Identität](../../assets/screens/de/ident.svg)

#### MAC-Hersteller

MAC → Hersteller in jedem Format; bei einer IP wird die MAC ermittelt. Virtuelle und lokal verwaltete Adressen markiert.

![MAC-Hersteller](../../assets/screens/de/mac.svg)

#### Nachbarschaft (LLDP/CDP)

Erkennung von Switch zu Switch; Portnamen, LAG, sieben Layouts, SVG / PNG / PDF.

![Nachbarschaft (LLDP/CDP)](../../assets/screens/de/nbr.svg)

### Pfad und Geschwindigkeit

#### Traceroute / MTR

Netzwerkspuren, Verlust und Latenz pro Hop, Weltkarte.

![Traceroute / MTR](../../assets/screens/de/trace.svg)

#### Geschwindigkeitstest

Download-/Upload-Messung ins Internet oder zum eigenen Server.

![Geschwindigkeitstest](../../assets/screens/de/speed.svg)

#### Wi-Fi

Signalmesser, Kanalansicht und Abdeckungskarte.

![Wi-Fi](../../assets/screens/de/wifi.svg)

#### Datei-Downloader

Schnelle Downloads über parallele Verbindungen, direkt in den Downloads-Ordner; SHA-256-Prüfung.

![Datei-Downloader](../../assets/screens/de/download.svg)

#### MTU-Ermittlung

Größtes Paket, das unfragmentiert durchkommt; Erkennung von Black Holes.

![MTU-Ermittlung](../../assets/screens/de/mtu.svg)

### DNS und Adresse

#### DNS-Abfrage

Eintragstypen, mehrere Server nebeneinander vergleichen, DNSSEC, AXFR.

![DNS-Abfrage](../../assets/screens/de/dns.svg)

#### Whois

RDAP und klassisches Whois: Registrar, Kontakte, AS, Standort, Rohdaten.

![Whois](../../assets/screens/de/whois.svg)

#### Meine öffentliche IP

Ermittelt öffentliche Adresse, Provider und DNS-Umleitung.

![Meine öffentliche IP](../../assets/screens/de/myip.svg)

### Web

#### HTTP/HTTPS-Übersicht

Statuscode, Weiterleitungen, Sicherheitsheader und Produkterkennung.

![HTTP/HTTPS-Übersicht](../../assets/screens/de/http.svg)

#### HTTP-Anfrage (curl)

DNS, TCP, TLS und erstes Byte einzeln; auch Seiten, die JavaScript benötigen.

![HTTP-Anfrage (curl)](../../assets/screens/de/curl.svg)

#### API-Client

Wie Postman, aber schlicht: Sammlungen, Variablen, Identität.

![API-Client](../../assets/screens/de/api.svg)

#### Zertifikat

Kette, Ablaufdatum, Vertrauen und TLS-Versionen.

![Zertifikat](../../assets/screens/de/cert.svg)

#### SSL-Prüfung

Eine Note von A+ … F nahe an den SSL-Labs-Kriterien, mit Begründung.

![SSL-Prüfung](../../assets/screens/de/ssl.svg)

### Verwaltung

#### Stapelverarbeitung

Befehle auf Hunderten von Rechnern per SSH / WinRM; Vorlagen, mehrere Identitäten.

![Stapelverarbeitung](../../assets/screens/de/exec.svg)

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, Testnachricht und Relay-Test.

![Mail](../../assets/screens/de/mail.svg)

#### SNMP

Walk / Get, v1–v3; im Broadcast-Modus antwortet der Computer wie ein SNMP-Gerät.

![SNMP](../../assets/screens/de/snmp.svg)

#### Syslog

Nachricht senden oder als Server eingehende Nachrichten empfangen.

![Syslog](../../assets/screens/de/syslog.svg)

#### Port-Nachricht / Lauschen

Nachricht an einen TCP- / UDP-Port senden und die Antwort oder eingehenden Verkehr beobachten.

![Port-Nachricht / Lauschen](../../assets/screens/de/send.svg)

#### Paketaufzeichnung

Leichte Aufzeichnung ohne Npcap, Protokollübersicht und pcap-Speicherung.

![Paketaufzeichnung](../../assets/screens/de/capture.svg)

#### Wake-on-LAN

Per Magic Packet aufwecken, und den Start per Ping verfolgen.

![Wake-on-LAN](../../assets/screens/de/wol.svg)

### Konto und Info

#### Subnetz berechnen

Netzwerk, Broadcast, nutzbarer Bereich, Maske und Aufteilung.

![Subnetz berechnen](../../assets/screens/de/subnet.svg)

#### Dieser Computer

Schnittstellen, adresler, Gateway, DNS und VPN.

![Dieser Computer](../../assets/screens/de/local.svg)

## Neden AdminsTools

- **Schnell, aber der Computer bleibt flüssig** — Pings gehen in gleichmäßigem Strom hinaus: Switches werden nicht überlastet, keine Antwort geht verloren. Das Programm läuft mit niedriger Priorität auf wenigen Kernen.
- **Starker Filter** — Fertige Schaltflächen, Wertelisten mit Anzahl, Bereiche und eine kurze Suchsprache: `vendor:hp rtt>20 -down`. Zeilen bleiben an ihrem Platz.
- **Ergebnisverlauf und Export** — Jeder Lauf wird aufbewahrt und unter seinem Namen gespeichert. Excel, CSV, pcap, SVG / PNG / PDF; Dateien direkt in den Downloads-Ordner.
- **Passworttresor** — SSH-, WinRM-, SNMP-v3- und Mail-Passwörter liegen in einem mit Argon2id + AES-GCM verschlüsselten Tresor; sie landen nie in Einstellungs- oder Ergebnisdateien.
- **Ihre Daten bleiben auf Ihrem Computer** — Kein Konto, keine Cloud, keine Telemetrie. Die Oberfläche öffnet sich nur auf 127.0.0.1 und mit Sitzungsschlüssel.
- **5 Sprachen, 9 Designs** — Türkisch, Englisch, Deutsch, Russisch, Chinesisch. Helle und dunkle Designs; Spaltenbreiten und Ansichten werden gespeichert.

## Herunterladen

Version 2.21.0 · Eine Datei: herunterladen und starten. Die Einstellungen stehen in einer Datei; legen Sie `PowerAdminTool.json` neben die exe, dann läuft es portabel vom USB-Stick.

**Windows** — `AdminsTools-2.21.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- Keine Installation und keine Administratorrechte nötig
- Ping und Traceroute ohne Treiber

**macOS** — `AdminsTools-2.21.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 und neuer) oder Intel
- Nicht signiert: beim ersten Start Rechtsklick › Öffnen
- Keine Paketaufzeichnung unter macOS

**Linux** — `adminstools-2.21.0-linux-amd64 · ~15 MB`

- x86-64, eine einzige Binärdatei
- `-listen 0.0.0.0:8090` für den Browserzugriff auf einem Jump-Server
- Für Ping: `ping_group_range` oder `cap_net_raw`

---

© 2026 Mehmet Göğebakan
