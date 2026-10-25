<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="../../assets/wordmark-dark.png"><img src="../../assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <b>English</b> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a></p>

<p align="center">The network and system administrator's toolbox in a single window: discovery, path and speed, DNS, web, mail, remote management — no installation, driver or account needed.</p>

<p align="center">✓ Single file, no installation &nbsp;·&nbsp; ✓ No admin rights needed &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Data stays on your computer</p>

## Screenshots

### Discovery

#### Ping sweep

A /24 in one round: latency, ARP, loss, name and MAC vendor; 5 pings or continuous to a single address.

![Ping sweep](../../assets/screens/en/ping.svg)

#### Port scan

Ready profiles, service banners, UDP probes; risky ports flagged.

![Port scan](../../assets/screens/en/port.svg)

#### IP ID

"What is this IP?" Ping, ports, SNMP, web and MAC combined into a scored guess with reasons.

![IP ID](../../assets/screens/en/ident.svg)

#### MAC vendor

MAC → vendor in any format; type an IP to find its MAC. Virtual and locally administered addresses flagged.

![MAC vendor](../../assets/screens/en/mac.svg)

#### Neighbors (LLDP/CDP)

Switch-to-switch discovery; port names, LAG, seven layouts, SVG / PNG / PDF.

![Neighbors (LLDP/CDP)](../../assets/screens/en/nbr.svg)

### Path and speed

#### Traceroute / MTR

Network lanes, loss and latency at every hop, world map.

![Traceroute / MTR](../../assets/screens/en/trace.svg)

#### Speed test

Download / upload speed to the internet or your own server.

![Speed test](../../assets/screens/en/speed.svg)

#### Wi-Fi

Signal meter, channel view and coverage map.

![Wi-Fi](../../assets/screens/en/wifi.svg)

#### File downloader

Fast downloads over parallel connections, straight to the Downloads folder; SHA-256 check.

![File downloader](../../assets/screens/en/download.svg)

#### MTU discovery

Largest packet that passes without fragmenting; black hole detection.

![MTU discovery](../../assets/screens/en/mtu.svg)

### DNS and address

#### DNS query

Record types, several servers compared side by side, DNSSEC, AXFR.

![DNS query](../../assets/screens/en/dns.svg)

#### Whois

RDAP and classic whois: registrar, contacts, AS, location, raw record.

![Whois](../../assets/screens/en/whois.svg)

#### My public IP

Detects your public address, provider and DNS redirection.

![My public IP](../../assets/screens/en/myip.svg)

### Web

#### HTTP/HTTPS summary

Status code, redirects, security headers and product guess.

![HTTP/HTTPS summary](../../assets/screens/en/http.svg)

#### HTTP request (curl)

DNS, TCP, TLS and first byte separately; pages that run on JavaScript too.

![HTTP request (curl)](../../assets/screens/en/curl.svg)

#### API client

Like Postman, but simple: collections, variables, identity.

![API client](../../assets/screens/en/api.svg)

#### Certificate

Chain, expiry date, trust and TLS versions.

![Certificate](../../assets/screens/en/cert.svg)

#### SSL audit

An A+ … F grade close to SSL Labs criteria, with reasons.

![SSL audit](../../assets/screens/en/ssl.svg)

### Management

#### Bulk action

Commands on hundreds of machines over SSH / WinRM; templates, multiple identities.

![Bulk action](../../assets/screens/en/exec.svg)

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, test message and relay test.

![Mail](../../assets/screens/en/mail.svg)

#### SNMP

Walk / get, v1–v3; in broadcast mode the computer answers like an SNMP device.

![SNMP](../../assets/screens/en/snmp.svg)

#### Syslog

Send a message, or act as a server and listen for incoming ones.

![Syslog](../../assets/screens/en/syslog.svg)

#### Port message / listen

Send a message to a TCP / UDP port and watch the reply, or listen for incoming traffic.

![Port message / listen](../../assets/screens/en/send.svg)

#### Packet capture

Lightweight capture without Npcap, protocol summary and pcap recording.

![Packet capture](../../assets/screens/en/capture.svg)

#### Wake-on-LAN

Wake with a magic packet, and watch it boot with ping.

![Wake-on-LAN](../../assets/screens/en/wol.svg)

### Calculations and info

#### Subnet calc

Network, broadcast, usable range, mask and splitting.

![Subnet calc](../../assets/screens/en/subnet.svg)

#### This computer

Interfaces, adresler, gateway, DNS and VPN.

![This computer](../../assets/screens/en/local.svg)

## Neden AdminsTools

- **Fast, but it won't slow your computer down** — Pings go out in a steady stream: switches aren't overwhelmed and no replies are lost. The program runs at low priority on a few cores.
- **Powerful filter** — Preset buttons, value lists with counts, ranges and a short query language: `vendor:hp rtt>20 -down`. Rows stay in place.
- **Result history and export** — Every run is kept and saved by name. Excel, CSV, pcap, SVG / PNG / PDF; files go straight to Downloads.
- **Password vault** — SSH, WinRM, SNMP v3 and mail passwords live in a vault encrypted with Argon2id + AES-GCM; never written to settings or result files.
- **Your data stays on your computer** — No account, cloud or telemetry. The interface opens only on 127.0.0.1, with a session key.
- **5 languages, 9 themes** — Turkish, English, German, Russian, Chinese. Light and dark themes; column widths and views are remembered.

## Download

Version 2.20.0 · A single file: download and run. Settings live in one file; put `PowerAdminTool.json` next to the exe and it runs portable from a USB stick.

**Windows** — `AdminsTools-2.20.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- No installation or admin rights needed
- Ping and traceroute need no driver

**macOS** — `AdminsTools-2.20.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 and later) or Intel
- Unsigned: right-click on first launch › Open
- No packet capture on macOS

**Linux** — `adminstools-2.20.0-linux-amd64 · ~15 MB`

- x86-64, a single binary
- `-listen 0.0.0.0:8090` for browser access on a jump server
- For ping: `ping_group_range` or `cap_net_raw`

---

© 2026 Mehmet Göğebakan
