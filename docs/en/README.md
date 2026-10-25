<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <b>English</b> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a></p>

<p align="center">The network and system administrator's toolbox in a single window: discovery, path and speed, DNS, web, mail, remote management — no installation, driver or account needed.</p>

<p align="center">✓ Single file, no installation &nbsp;·&nbsp; ✓ No admin rights needed &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Data stays on your computer</p>

<p align="center"><a href="http://adminstools.org/downloads/AdminsTools-2.23.0.exe"><b>Windows</b></a> <sub>.exe · ~16 MB</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **27** | **1** | **256** | **5** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| tools in one window | file; no installation | addresses /24 in one round | languages: TR · EN · DE · RU · 中文 | colour themes, dark included |

## Screenshots

Every tool's screen, drawn with its layout in the program; click to enlarge.

| Discovery | Path and speed | DNS and address | Web | Management | Calculations and info |
|---|---|---|---|---|---|
| [Ping sweep](#t-ping) | [Traceroute / MTR](#t-trace) | [DNS query](#t-dns) | [HTTP/HTTPS summary](#t-http) | [Bulk action](#t-exec) | [Subnet calc](#t-subnet) |
| [Port scan](#t-port) | [Speed test](#t-speed) | [Whois](#t-whois) | [HTTP request (curl)](#t-curl) | [Mail](#t-mail) | [This computer](#t-local) |
| [IP ID](#t-ident) | [Wi-Fi](#t-wifi) | [My public IP](#t-myip) | [API client](#t-api) | [SNMP](#t-snmp) |  |
| [MAC vendor](#t-mac) | [File downloader](#t-download) |  | [Certificate](#t-cert) | [Syslog](#t-syslog) |  |
| [Neighbors (LLDP/CDP)](#t-nbr) | [MTU discovery](#t-mtu) |  | [SSL audit](#t-ssl) | [Port message / listen](#t-send) |  |
|  |  |  |  | [Packet capture](#t-capture) |  |
|  |  |  |  | [Wake-on-LAN](#t-wol) |  |

### Discovery

<a id="t-ping"></a>

#### Ping sweep

A /24 in one round: latency, ARP, loss, name and MAC vendor; 5 pings or continuous to a single address.

![Ping sweep](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/ping.svg)

<a id="t-port"></a>

#### Port scan

Ready profiles, service banners, UDP probes; risky ports flagged.

![Port scan](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/port.svg)

<a id="t-ident"></a>

#### IP ID

"What is this IP?" Ping, ports, SNMP, web and MAC combined into a scored guess with reasons.

![IP ID](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/ident.svg)

<a id="t-mac"></a>

#### MAC vendor

MAC → vendor in any format; type an IP to find its MAC. Virtual and locally administered addresses flagged.

![MAC vendor](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/mac.svg)

<a id="t-nbr"></a>

#### Neighbors (LLDP/CDP)

Switch-to-switch discovery; port names, LAG, seven layouts, SVG / PNG / PDF.

![Neighbors (LLDP/CDP)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/nbr.svg)

### Path and speed

<a id="t-trace"></a>

#### Traceroute / MTR

Network lanes, loss and latency at every hop, world map.

![Traceroute / MTR](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/trace.svg)

<a id="t-speed"></a>

#### Speed test

Download / upload speed to the internet or your own server.

![Speed test](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/speed.svg)

<a id="t-wifi"></a>

#### Wi-Fi

Signal meter, channel view and coverage map.

![Wi-Fi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/wifi.svg)

<a id="t-download"></a>

#### File downloader

Fast downloads over parallel connections, straight to the Downloads folder; SHA-256 check.

![File downloader](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/download.svg)

<a id="t-mtu"></a>

#### MTU discovery

Largest packet that passes without fragmenting; black hole detection.

![MTU discovery](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/mtu.svg)

### DNS and address

<a id="t-dns"></a>

#### DNS query

Record types, several servers compared side by side, DNSSEC, AXFR.

![DNS query](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/dns.svg)

<a id="t-whois"></a>

#### Whois

RDAP and classic whois: registrar, contacts, AS, location, raw record.

![Whois](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/whois.svg)

<a id="t-myip"></a>

#### My public IP

Detects your public address, provider and DNS redirection.

![My public IP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/myip.svg)

### Web

<a id="t-http"></a>

#### HTTP/HTTPS summary

Status code, redirects, security headers and product guess.

![HTTP/HTTPS summary](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/http.svg)

<a id="t-curl"></a>

#### HTTP request (curl)

DNS, TCP, TLS and first byte separately; pages that run on JavaScript too.

![HTTP request (curl)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/curl.svg)

<a id="t-api"></a>

#### API client

Like Postman, but simple: collections, variables, identity.

![API client](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/api.svg)

<a id="t-cert"></a>

#### Certificate

Chain, expiry date, trust and TLS versions.

![Certificate](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/cert.svg)

<a id="t-ssl"></a>

#### SSL audit

An A+ … F grade close to SSL Labs criteria, with reasons.

![SSL audit](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/ssl.svg)

### Management

<a id="t-exec"></a>

#### Bulk action

Commands on hundreds of machines over SSH / WinRM; templates, multiple identities.

![Bulk action](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/exec.svg)

<a id="t-mail"></a>

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, test message and relay test.

![Mail](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/mail.svg)

<a id="t-snmp"></a>

#### SNMP

Walk / get, v1–v3; in broadcast mode the computer answers like an SNMP device.

![SNMP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/snmp.svg)

<a id="t-syslog"></a>

#### Syslog

Send a message, or act as a server and listen for incoming ones.

![Syslog](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/syslog.svg)

<a id="t-send"></a>

#### Port message / listen

Send a message to a TCP / UDP port and watch the reply, or listen for incoming traffic.

![Port message / listen](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/send.svg)

<a id="t-capture"></a>

#### Packet capture

Lightweight capture without Npcap, protocol summary and pcap recording.

![Packet capture](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/capture.svg)

<a id="t-wol"></a>

#### Wake-on-LAN

Wake with a magic packet, and watch it boot with ping.

![Wake-on-LAN](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/wol.svg)

### Calculations and info

<a id="t-subnet"></a>

#### Subnet calc

Network, broadcast, usable range, mask and splitting.

![Subnet calc](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/subnet.svg)

<a id="t-local"></a>

#### This computer

Interfaces, adresler, gateway, DNS and VPN.

![This computer](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/en/local.svg)

## Neden AdminsTools

- **Fast, but it won't slow your computer down** — Pings go out in a steady stream: switches aren't overwhelmed and no replies are lost. The program runs at low priority on a few cores.
- **Powerful filter** — Preset buttons, value lists with counts, ranges and a short query language: `vendor:hp rtt>20 -down`. Rows stay in place.
- **Result history and export** — Every run is kept and saved by name. Excel, CSV, pcap, SVG / PNG / PDF; files go straight to Downloads.
- **Password vault** — SSH, WinRM, SNMP v3 and mail passwords live in a vault encrypted with Argon2id + AES-GCM; never written to settings or result files.
- **Your data stays on your computer** — No account, cloud or telemetry. The interface opens only on 127.0.0.1, with a session key.
- **5 languages, 9 themes** — Turkish, English, German, Russian, Chinese. Light and dark themes; column widths and views are remembered.

## Download

Version 2.23.0 · A single file: download and run. Settings live in one file; put `PowerAdminTool.json` next to the exe and it runs portable from a USB stick.

**Windows** — `AdminsTools-2.23.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- No installation or admin rights needed
- Ping and traceroute need no driver

[⤓ Download for Windows](http://adminstools.org/downloads/AdminsTools-2.23.0.exe)

**macOS** — `AdminsTools-2.23.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 and later) or Intel
- Unsigned: right-click on first launch › Open
- No packet capture on macOS

[⤓ Apple Silicon](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip)

**Linux** — `adminstools-2.23.0-linux-amd64 · ~15 MB`

- x86-64, a single binary
- `-listen 0.0.0.0:8090` for browser access on a jump server
- For ping: `ping_group_range` or `cap_net_raw`

[⤓ Download for Linux](http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64)

---

© 2026 Mehmet Göğebakan
