<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><b>Türkçe</b> &nbsp;·&nbsp; <a href="docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="docs/zh/README.md">中文</a></p>

<p align="center">Ağ ve sistem yöneticisinin tek pencerelik araç çantası: keşif, yol ve hız, DNS, web, posta, uzaktan yönetim — kurulum, sürücü ve hesap gerektirmeden.</p>

<p align="center">✓ Tek dosya, kurulum yok &nbsp;·&nbsp; ✓ Yönetici hakkı gerekmez &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Veriler bilgisayarda kalır</p>

<p align="center"><a href="http://adminstools.org/downloads/AdminsTools-2.23.0.exe"><b>Windows</b></a> <sub>.exe · ~16 MB</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **27** | **1** | **256** | **5** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| araç, tek pencerede | dosya; kurulum yok | adres /24 tek turda | dil: TR · EN · DE · RU · 中文 | renk teması, koyu dahil |

## Ekran görüntüleri

Her aracın ekranı, programdaki düzeniyle çizildi; büyütmek için tıklayın.

| Keşif | Yol ve hız | DNS ve adres | Web | Yönetim | Hesap ve bilgi |
|---|---|---|---|---|---|
| [Ping taraması](#t-ping) | [Traceroute / MTR](#t-trace) | [DNS sorgu](#t-dns) | [HTTP/HTTPS özeti](#t-http) | [Toplu işlem](#t-exec) | [Alt ağ hesap](#t-subnet) |
| [Port tarama](#t-port) | [Hız testi](#t-speed) | [Whois](#t-whois) | [HTTP istek (curl)](#t-curl) | [Mail](#t-mail) | [Bu bilgisayar](#t-local) |
| [IP kimliği](#t-ident) | [Wi-Fi](#t-wifi) | [Genel IP'm](#t-myip) | [API istemcisi](#t-api) | [SNMP](#t-snmp) |  |
| [MAC üretici](#t-mac) | [Dosya indirici](#t-download) |  | [Sertifika](#t-cert) | [Syslog](#t-syslog) |  |
| [Komşuluk (LLDP/CDP)](#t-nbr) | [MTU bulma](#t-mtu) |  | [SSL denetimi](#t-ssl) | [Port mesaj / dinle](#t-send) |  |
|  |  |  |  | [Paket yakalama](#t-capture) |  |
|  |  |  |  | [Wake-on-LAN](#t-wol) |  |

### Keşif

<a id="t-ping"></a>

#### Ping taraması

Bir /24 tek turda: gecikme, ARP, kayıp, ad ve MAC üreticisi; tek adrese 5 ping ya da sürekli.

![Ping taraması](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/ping.svg)

<a id="t-port"></a>

#### Port tarama

Hazır profiller, servis karşılamaları, UDP sondaları; riskli portlar işaretli.

![Port tarama](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/port.svg)

<a id="t-ident"></a>

#### IP kimliği

"Bu IP ne?" Ping, portlar, SNMP, web ve MAC birleşip gerekçeli, puanlı tahmin.

![IP kimliği](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/ident.svg)

<a id="t-mac"></a>

#### MAC üretici

Her biçimde MAC → üretici; IP yazılırsa MAC bulunur. Sanal ve yerel adresler işaretli.

![MAC üretici](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/mac.svg)

<a id="t-nbr"></a>

#### Komşuluk (LLDP/CDP)

Switch'ten switch'e keşif; port adları, LAG, yedi yerleşim, SVG / PNG / PDF.

![Komşuluk (LLDP/CDP)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/nbr.svg)

### Yol ve hız

<a id="t-trace"></a>

#### Traceroute / MTR

Ağ şeritleri, her atlamada kayıp ve gecikme, dünya haritası.

![Traceroute / MTR](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/trace.svg)

<a id="t-speed"></a>

#### Hız testi

İnternete ya da kendi sunucunuza indirme / yükleme ölçümü.

![Hız testi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/speed.svg)

<a id="t-wifi"></a>

#### Wi-Fi

Sinyal ölçer, kanal görünümü ve kapsama haritası.

![Wi-Fi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/wifi.svg)

<a id="t-download"></a>

#### Dosya indirici

Paralel bağlantılı hızlı indirme, doğrudan İndirilenler klasörüne; SHA-256 doğrulama.

![Dosya indirici](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/download.svg)

<a id="t-mtu"></a>

#### MTU bulma

Parçalanmadan geçen en büyük paket; kara delik tespiti.

![MTU bulma](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/mtu.svg)

### DNS ve adres

<a id="t-dns"></a>

#### DNS sorgu

Kayıt türleri, birden çok sunucuyu yan yana karşılaştırma, DNSSEC, AXFR.

![DNS sorgu](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/dns.svg)

<a id="t-whois"></a>

#### Whois

RDAP ve klasik whois: kayıt şirketi, kişiler, AS, konum, ham kayıt.

![Whois](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/whois.svg)

<a id="t-myip"></a>

#### Genel IP'm

Genel adres, servis sağlayıcı ve DNS yönlendirmesinin tespiti.

![Genel IP'm](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/myip.svg)

### Web

<a id="t-http"></a>

#### HTTP/HTTPS özeti

Durum kodu, yönlendirme, güvenlik başlıkları ve ürün tahmini.

![HTTP/HTTPS özeti](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/http.svg)

<a id="t-curl"></a>

#### HTTP istek (curl)

DNS, TCP, TLS, ilk bayt ayrı ayrı; JavaScript ile çalışan sayfalar da.

![HTTP istek (curl)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/curl.svg)

<a id="t-api"></a>

#### API istemcisi

Postman gibi, ama sade: koleksiyonlar, değişkenler, kimlik.

![API istemcisi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/api.svg)

<a id="t-cert"></a>

#### Sertifika

Zincir, bitiş tarihi, güven ve TLS sürümleri.

![Sertifika](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/cert.svg)

<a id="t-ssl"></a>

#### SSL denetimi

SSL Labs ölçütlerine yakın A+ … F notu ve nedenleri.

![SSL denetimi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/ssl.svg)

### Yönetim

<a id="t-exec"></a>

#### Toplu işlem

SSH / WinRM ile yüzlerce makinede komut; şablonlar, birden çok kimlik.

![Toplu işlem](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/exec.svg)

<a id="t-mail"></a>

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, deneme iletisi ve relay testi.

![Mail](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/mail.svg)

<a id="t-snmp"></a>

#### SNMP

Walk / get, v1–v3; yayın kipinde bilgisayar bir SNMP cihazı gibi yanıt verir.

![SNMP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/snmp.svg)

<a id="t-syslog"></a>

#### Syslog

İleti gönder ya da sunucu olup gelenleri dinle.

![Syslog](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/syslog.svg)

<a id="t-send"></a>

#### Port mesaj / dinle

TCP / UDP portuna mesaj gönder, yanıtı ya da gelenleri izle.

![Port mesaj / dinle](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/send.svg)

<a id="t-capture"></a>

#### Paket yakalama

Npcap'siz hafif yakalama, protokol özeti ve pcap kaydı.

![Paket yakalama](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/capture.svg)

<a id="t-wol"></a>

#### Wake-on-LAN

Sihirli paketle uyandır, açılmasını ping ile izle.

![Wake-on-LAN](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/wol.svg)

### Hesap ve bilgi

<a id="t-subnet"></a>

#### Alt ağ hesap

Ağ, yayın, kullanılabilir aralık, maske ve bölme.

![Alt ağ hesap](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/subnet.svg)

<a id="t-local"></a>

#### Bu bilgisayar

Arayüzler, adresler, ağ geçidi, DNS ve VPN.

![Bu bilgisayar](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@23ff1b43dc05/assets/screens/tr/local.svg)

## Neden AdminsTools

- **Hızlı, ama bilgisayarı kasmaz** — Pingler düzenli akışla gider: anahtarlama cihazları yorulmaz, yanıt kaybolmaz. Program düşük öncelikte ve birkaç çekirdekle çalışır.
- **Güçlü süzgeç** — Hazır düğmeler, sayılı değer listeleri, aralıklar ve kısa arama dili: `vendor:hp rtt>20 -down`. Satırlar yerinden oynamaz.
- **Sonuç geçmişi ve dışa aktarma** — Her çalıştırma saklanır, adıyla kaydedilir. Excel, CSV, pcap, SVG / PNG / PDF; dosyalar doğrudan İndirilenler'e.
- **Şifre kasası** — SSH, WinRM, SNMP v3 ve mail şifreleri Argon2id + AES-GCM ile şifreli kasada; ayar ve sonuç dosyalarına yazılmaz.
- **Veri bilgisayarınızda** — Hesap, bulut, telemetri yok. Arayüz yalnızca 127.0.0.1'de ve oturum anahtarıyla açılır.
- **5 dil, 9 tema** — Türkçe, English, Deutsch, Русский, 中文. Açık ve koyu temalar; sütun genişlikleri ve görünümler hatırlanır.

## İndir

Sürüm 2.23.0 · Tek dosya: indirin ve çalıştırın. Ayarlar tek bir dosyada; exe'nin yanına `PowerAdminTool.json` koyarsanız USB bellekten taşınabilir çalışır.

**Windows** — `AdminsTools-2.23.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- Kurulum ve yönetici hakkı gerekmez
- Ping ve traceroute sürücü istemez

[⤓ Windows için indir](http://adminstools.org/downloads/AdminsTools-2.23.0.exe)

**macOS** — `AdminsTools-2.23.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 ve sonrası) ya da Intel
- İmzasız: ilk açılışta sağ tık › Aç
- Paket yakalama macOS'ta yok

[⤓ Apple Silicon](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip)

**Linux** — `adminstools-2.23.0-linux-amd64 · ~15 MB`

- x86-64, tek ikili dosya
- `-listen 0.0.0.0:8090` ile atlama sunucusunda tarayıcıdan
- Ping için `ping_group_range` ya da `cap_net_raw`

[⤓ Linux için indir](http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64)

---

© 2026 Mehmet Göğebakan
